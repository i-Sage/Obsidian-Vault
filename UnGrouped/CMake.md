2023-09-03  ---  17:44
Type : Reference
Tags : #cmake
___
# Modern CMake
---
In software development, CMake is cross-platform free and open-source software for build automation, testing, packaging and installation of software by using a compiler-independent method. CMake is not a build system itself; it generates another system's build files.
## Targets
A target is a logical unit in an application, i.e you might have an application made up of several libraries, and each of those libraries is a target, source code is usually organised into logical units to give birth to those binaries. It is possible for a target to propagate it's properties to other targets that depend on it. For example if lib_b depends on lib_a, it is possible to get lib_a's include path from lib_b. When thinking about the keywords PUBLIC, INTERFACE and PRIVATE, it is import to think about it from the perspective of the owner and also the perspective of the consumer of the property. For example, when we use the PUBLIC keyword on target_include_directories i.e:
```cmake
target_include_directories(lib_a PUBLIC ${CMAKE_CURRENT_LIST_DIR}/include)
```
we are implying that that other targets that depend on lib_a will also have access to this include directory for lib_a. This means that if lib_b depends on lib_a, lib_b will have access to lib_a's include directory. This means that this property is INHERITED!!.
As for the INTERFACE keyword, this states that this property will be available for targets that depends on this library, but this library will not necessarily use this property.
The PRIVATE keyword states that this library will own and use this property and will not make it available to other targets that depend on this library
## Project Structure
```
- ${Project_Name}
	- .gitignore
	- .clangd
	- run.sh
	- CMakeLists.txt
	- CMakeUserPresets.json
	- compile_commands.json
	- README.md
	- CHANGELOG.md
	- src
		- CMakeLists.txt
		- main.cxx
		- lib
			- main
				- CMakeLists.txt
				- main.hxx
	- tests
		- CMakeLists.txt
		- test.cxx
	- third_party
		- CMakeLists.txt
		- fmt
		- Catch2
		- patterns
```
## Handy env vars
```cmake
CMAKE_BUILD_TYPE(Release, Debug, RelWitDebInfo MinSizeRel)
CMAKE_CONFIGURATION_TYPES
CMAKE_EXPORT_COMPILE_COMMANDS(ON, OFF)
CMAKE_BUILD_PARALLEL(no_of_processes_for_building)
CMAKE_COLOR_DIAGNOSTICS(ON, OFF)
```

## The classic CMake Build Procedure:
```shell
mkdir build
cd build
cmake ..
make
```
You can replace the `make` line with `cmake --build .` 

## Using a Newer version of CMake:
```shell
cmake -S . -B build
cmake --build build
```
## Using and Selecting Presets
```bash
# list user presets
cmake --list-presets

# pick a preset
cmake . --preset ${preset_name}

# build project
cmake --build --preset ${build_preset}
```
## Any of these commands will Install:
```shell
# From the build directory (pick one)
make install
cmake --build . --target install
cmake --install . # CM
ake 3.15+ only

# From the source directory (pick one)
cmake -C build install
cmake --build build --target install
cmake --install build # CMake 3.15+ only
```
## Picking a compiler
Selecting a compiler must be done on the first run in an empty directory.
```shell
# To pick clang
CC=clang CXX=clang++ cmake ..

# To pick gcc
CC=gcc CXX=g++ cmake ..
```

# Picking a generator
You can build with a variety of tools; `make` is usually the default. To see all the tools CMake knows about on your system, run
```shell
cmake --help
```
And you can pick a tool with `-G"My Tool"` <b>(quotes only needed if spaces are in the tool name)</b>. You should pick a tool on your first CMake call in a directory, just like the compiler. Feel free to have several build directories, like build/ and buildXcode/ . You can set the environment variable `CMAKE_GENERATOR` to control the default generator (CMake 3.15+)
<b>NOTE</b> that makefiles will only run in parallel if you explicitly pass a number of threads, such as `make -j2`, while Ninja will automatically run in parallel.
You can directly pass a parallelization on option such as `j2` to the `cmake --build .` command in recent versions of CMake.

## Setting Options
You can set options in CMake with `-D`  . You can see a list of options with `-L`, or a list with human-readable help with `-LH`. If you don't list the source/build directory, the listing will not rerun CMake(`cmake -L` instead of `cmake -L`.)

## Verbose and partial builds
<b>NOTE</b> not all build tools support it, you can get verbose builds (pick one):
```shell
cmake --build build --verbose #CMake 3.14+ only
VERBOSE=1 make
```
You can also build just a part of a build by specifying a target as the name of a library or executable you've defined in CMake, and make will just build that target

# Options
CMake has support for cached options. A Variable in CMake can be marked as "cached", which means it will be written to the cache (a file called `CMakeCache.txt` in the build directory) when it is encountered, You can preset (or change) the value of a cached option on the command line with `-D` . When CMake looks for a cached variable, it will use the existing value and will not overwrite it.

# Standard Options
These are common CMake Options to most packages:
- `-DCMAKE_BUILD_TYPE` Pick from Release, RelWithDebInfo, Debug or sometimes more.
- `-DCMAKE_INSTALL_PREFIX=` The location to install to. System install on UNIX would often be /usr/local (the default), user directries are ofter `~/.local` or you can pick a folder.
- `-DBUILD_SHARED_LIBS=` You can set this `ON` or `OFF` to control the default for shared libraries 
- `-DBUILD_TESTING=` This is a common name for enabling tests, not all packages use it, sometimes with good reason.


## Do's and Don'ts
#### CMake Antipatterns
- <b>Do not use global functions:</b> This includes `link_directories`, `include_libraries`, and similar.
- <b>Don't add unneeded PUBLIC requirnments:</b>You should avoid forcing something on users that is not required (`-Wall`). Make these PRIVATE instead.
- <b>Don't GLOB files:</b> Make or another tool will not know if you add files without rerunning CMake. Note that CMake 3.12 adds a `CONFIGURE_DEPENDS` flag that makes this far better if you need to use it.
- <b>Link to build files directly:</b> Always link to targets if available.
- <b>Never skip PUBLIC/PRIVATE when linking:</b> This causes all future linking to be keyword-less.


## CMake Patterns
- <b>Treat CMake as code:</b> It is code. It should be as clean and readable as all other code.
- <b>Think in targets:</b> Your targets should represent concepts. Make an (IMPORTED) INTERFACE target for anything that should stay together and link to that.
- <b>Export your interface:</b> You should be able to run from build or install
- <b>Write a Cnfig.cmake file:</b> This is what a library author should do to support clients.
- <b>Make ALIAS targets to keep usage consistent:</b> Using `add_subdirectory` and `find_package` should provide the same targets and namespaces.
- <b>Combine common functionality into clearly documented functions or macros:</b> Functions are better usually.
- <b>Use lowercase function name:</b> CMake functions and macros can be called lower or uppercase. Always use lowercase. Uppercase is for variables.
- <b>Use cmake_policy and/or range of versions:</b> Policies change for a reason. Only piecemeal set OLD policies if you  have to .
---
### References
---
[cmake](https://cmake.org/overview/)