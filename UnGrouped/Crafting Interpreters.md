>Fairy tales are more than true: not because they
>tell us that dragons exist, but because they tell us
>that dragons can be beaten.
>
> 									— Neil Gaiman, Coraline 

#### "Self-hosting"
you can implement a compiler in any language, including the same language it compiles, a process called <b>"self-hosting"</b>
#### "Boot-Strapping"
You can't compile your compiler using itself yet, but if you have another compiler for you language written in some other language, you use <i>that</i> one to compile your compiler once. Now you can use the compiled version of your compiler to compile future versions of itself and you can discard the original one compiled from the other compiler. This is called <b>"boot-strapping</b>" from the image of pulling yourself up by your own boot-straps. ![[Pasted image 20230901105100.png]]

## A map of the Territory
>You must have a map, no matter how rough.
>Otherwise you wander all over the place. In “The
>
>Lord of the Rings” I never made anyone go
>farther than he could on a given day.

>										— J.R.R. Tolkien

### The Parts of a language
![[Pasted image 20230901105545.png]]
I Visualise the network of paths as an implementation one may choose as climbing a mountain. You start off at the bottom with the program as raw source text, literally just a string of characters. Each phase analyzes the program and transforms it to some higher-level representation where the semantics -- what the author wants the computer to do -- becomes more apparent

Eventually we reach the peak. We have a bird's eye view of the user's program and we can see what the code <i>means</i>. We begin our descent down the otherside of the mountain. We transform the highest-level representation down to successively lower-level forms to get closer and closer to something we know how to make the CPU actually execute.

Let's trace through each of those traits and points of interest. Our journey begins on the left side with the bare text of the user's source code:
![[Pasted image 20230901111021.png]]

- ### Scanning :
	The first stem is <b><i>scanning</i></b> also known as <b><i>lexing</i></b>, or (if you are trying to impress someone) <b><i>lexical analysis</i></b>. They all mean pretty much the same thing. 

	A <b><i>scanner</i></b> (or <b><i>lexer</i></b>) takes in the linear stream of characters and chunks them together into a series of something more akin to "words". In programming languages, each of these words is called a <b><i>token</i></b>. Some tokens are single characters like ( and , . Others may be several characters long, like numbers (123), string literals ("hi!"), and identifiers (min).

	Some characters in a source file don't actually mean anything, White-space is often insignificant and comments by definition, are ignored by the language. The scanner usually discards these, leaving a clean sequence of meaningful tokens.
	![[Pasted image 20230901111034.png]]

- ### Parsing :
	The next step is <b><i>parsing</i></b>. This is where our syntax gets a <b><i>grammar</i></b> -- The ability to compose larger expressions and statements out of smaller parts.

	The <b><i>parser</i></b> takes a sequence of tokens and builds a tree structure that mirrors the nested nature of grammar. These trees have a couple of different names -- <b><i>"parse tree"</i></b> or <b><i>"abstract syntax tree"</i></b> -- depending on how close to the bare syntactic structure of the source language they are. In practice, language hackers usually call them <b><i>"syntax trees"</i></b>, <b><i>"ASTs"</i></b>, or often just <b><i>"trees".</i></b>
![[Pasted image 20230901111756.png]]


- ### Static analysis :
	The first two stages are pretty much similar across all implementations. Now, the individual characteristics of each language start coming into play. At this point, we know the syntactic structure of the code --things like which expressions are nested in which other --but we don't know much more about that.

	In an expression like `a + b`, we know we are adding a and b, but we don't know what those names refer to. Are they local variables ? Global? Where are they defined?

	The first bit of analysis that most languages do is called <b><i>binding</i></b> or <b><i>resolution</i></b>. For each <b><i>identifier</i></b> we find out where that name is defined and write the two together. This is where <b><i>scope</i></b> comes into play --the region of source code where a certain name can be used to refer to a certain declaration. 

	If the language is statically typed, this is when we type check. Once we know where a and b are declared, we can also figure out their types. Then if those types don't support being added to each other, we report a <b><i>type error</i></b>.

	Take a deep breath. We have attained the summit of the mountain and a sweeping view of the user's program. All this semantic insight that is visible to use from analysis need to be stored somewhere. There are a few places we can squirrel it away:
		1. often, it gets stored right back as <b><i>attributes</i></b> on the syntax tree itself --extra fields in the nodes that aren't initialized during parsing but get filled in later.
		2. other times, we may store in a look-up table off to the side. Typically the keys to this table are identifiers-names of variables and declarations. In that case, we call it a <b><i>symbol table</i></b> and the values it associates with each key tells us what the identifer refers to.
		3. The most powerful bookkeeping tool is to transform the tree into an entirely new data structure more directly expresses the semantic of the code.

	Everything up to this point is considered the <b><i>front end</i></b> of the implementation. You might guess everything after this is the <b><i>back end</i></b>, but no. Back in the old days of yore when "front end" and "back end" were coined, compilers were much simpler. Later researchers invented new phases to stuff between the two halves. Rather than discard the old terms, William Wulf and company lumped them into charming but spatially paradoxical name <b><i>middle end</i></b>.

### Intermediate representations: 
   you can think of the compiler as a pipeline where each stage's job is to organize the data representing the user's code in a way that makes the next stage simpler to implement. The front end of the pipeline is specific to the source language the program is written in. The back end is concerned with  the final architecture where the program will run

   In the middle, the code may be stored in some <b><i>intermediate representation</i></b> (or <b>IR</b>) that isn't tightly tied to either the source or destination forms (hence "intermediate"). Instead, the IR acts as an interface between these two languages.

   This lets you support multiple source languages and target platforms with less effort. Say you want to implement Pascal, C and Fortran compilers and you want to target x86, ARM, and maybe SPARC. Normally, that means you're signing up to write nine full compilers Pascal->x86, C-ARM, and every other combination. A shared intermediate representation reduces that dramatically. You write one front end for each source language that produces the IR. then one backend for each target architecture. Now you can mix and match those to get every combination.

   There's another big reason we might want to transform the code into a form that makes the semantics more apparent...
```
There are a few well-established styles of IRs
out there. Hit your search engine of choice
and look for “control flow graph”, “static
single-assignment”, “continuation-passing
style”, and “three-address code”.
```

```
If you’ve ever wondered how GCC supports
so many crazy languages and architectures,
like Modula-3 on Motorola 68k, now you
know. Language front ends target one of a
handful of IRs, mainly GIMPLE and RTL.
Target backends like the one for 68k then
take those IRs and produce native code.
```

### Optimization : 
   Once we understand what the user's program means, we are free to swap it out with a different program that has the <i>same semantics</i> but implements them more efficiently --we can <b>optimize</b> it.

   A simple example is <b>constant folding</b>: if some expression always evaluates to the exact same value, we can do the evaluation at compile time and replace the code for the expression with its result. If the user typed in: 
```
penny_area = 3.14159 * (0.75/2) * (0.75/2);
```

we can do all of that arithmetic in the compiler and change the code into: 
```
pennyArea = 0.4417860938;
```
Optimization is a huge part of the programming lanugage business. Many language hackers sped their entire careers here, squeezing every drop of performance they can out of their compilers to get their benchmarks a fraction of a percent faster. It can become a sort of obsession.

We're mostly going to hop over that rathole in this book. Many successful languages have surprisingly few compile-time optimizations. For example, Lua and CPython generate relatively unoptimized code, and focus most of their performance effort on the runtime.

```
If you can’t resist poking your foot into that
hole, some keywords to get you started are
“constant propagation”, “common
subexpression elimination”, “loop invariant
code motion”, “global value numbering”,
“strength reduction”, “scalar replacement of
aggregates”, “dead code elimination”, and
“loop unrolling”.
```

### Code generation: 
We have applied all the optimaiztion we can think of to the user's progarm. The last step is converting it to a form the machine can actually run. In other words <b><i>generating code</i></b> (or <b><i>code gen</i></b>), where "code" here usually refers to the "source code" a human might want to read.


Finally, we are in the <b><i>Back end</i></b>, descending the other side of the mountain. From here on out, our representation of the code becomes more and more primitive, <i>like evolution run in reverse</i>, as we get closer to something our simple-minded machine can understand.


We have a decision to make. Do we generate instruction for a real CPU or a virtual one?. If we generate real machine code, we get an exectuable that the OS can load directly onto the chip. Native code is lighting fast, but generally it is a lot of work. Today's architectures have piles of instructions, complex pipelines, and enough historical baggage to fill a 747's luggage bay.

Speaking the chip's language also means your compiler is tied to a specific architecture. If your compiler targets x86 machine code, it is not going to run on ARM devices. This generates a Portability issue.

To get around this portability issue, hackers like Martin Richards and Niklaus Wirth, of BCPL and Pascal Fame, respectively, made their produce <i>virtual</i> machine code. Instead of instructions for some real chip, they produced code for a hypothetical, idealized machine. Wirth called this <b><i>"p-code"</i></b> for <b><i>"portable"</i></b>, but today, we generally call it <b><i>bytecode</i></b> because each instruction is often a single byte long.

These synthetic instructions are designed to map a little more closely to the language's semantics, and not be so tied to the peculiarities of any one computer architecture and its accumulated historical cruff. You can think of it like a dense binary encoding of the languag's low-level operations.

### Virtual Machine :
If your compiler produces bytecode, your work isn't over once that's done. Since there is no chip that speaks bytecode, it's your job to translate. Again, you have two options. You can write a little mini-compiler for each target architecture that converts the byte code to native code for that machine. You still have to do work for each chip you support, but this last stage is pretty simple and you get to reuse the rest of the compiler pipeline across all of the machines you support. You are basically using your bytecode as an intermediate representation.

Or you can write a <b><i>Virtual Machine</i></b>, a program that emulates a hypothetical chip supporting your virtual architecture at runtime. Running bytecode in a VM is slower than translating it to native code ahead of time because every instruction must be simulated aat runtime each time it executes. In return, you get simplicity and portablility. Implement your VM in, say, C, and you can run your language on any platform that has a C compiler.

```
The basic principle here is that the farther
down the pipeline you push the architecture-
specific work, the more of the earlier phases
you can share across architectures.
There is a tension, though. Many
optimizations, like register allocation and
instruction selection, work best when they
know the strengths and capabilities of a
specific chip. Figuring out which parts of
your compiler can be shared and which
should be target-specific is an art.
```

```
The term “virtual machine” also refers to a
different kind of abstraction. A system
virtual machine emulates an entire
hardware platform and operating system in
software. This is how you can play Windows
games on your Linux machine, and how
cloud providers give customers the user
experience of controlling their own “server”
without needing to physically allocate
separate computers for each user.
The kind of VMs we’ll talk about in this book
are language virtual machines or process
virtual machines if you want to be
unambiguous.
```


### Runtime :
Finally we finally hammered the user's program into a form that we can execute. The last step is running it. If we compiled it to machine code, we simply tell the operating system to load the executable and off it goes. If we complied it to bytecode, we need to startup the VM and load the program into that.

In both cases, for all the but the basest of low-level languages, we usually need some services that our language provides while the program is running. For example, if the language automatically manages memory, we need a <b>garbage collector</b> going in order to reclame unused bits. If our language supports "instance of" tests so you can see what kind of object you have, then we need some representation to keep track of the type each object during execution.

All of this stuff is going at runtime, so it's called appropriately, the <b>runtime</b>. In a fully compiled language, the code implementing the runtime gets inserted directly into the resulting executable. In, say, Go, each complied application has its own copy of Go's runtime directly embedded in it. If the language is run inside an interpreter or VM, then the runtime lives there. This is how most implementations of languages like Java, Python and JavaScript work.


### ShortCuts and Alternate Routes :
Thats The long path convering every possible phase you might implement. Many languages do walk the entire route, but there are few shortcuts and alternate paths

#### Single-pass compilers:
Some simple compilers interleave parsing, anaylsis, and code generation so that they produce output code directly in the parser, without ever allcationg any syntax trees or other IRs. These <b>single-pass compilers</b> restrict the design of the language. You have no intermediate data structure to store global information about the program, and you don't revisit any previously parsed part of the code. That means as soon as you see some expression, you need to know enough to correctly compile it.

Pascal and C were designed around this limitaion. At the time, memory was so precious that a compiler might not even be able to hold an entire source file in memory, much less the whole program. This is why Pascal's grammar requires type declarations to appear in a block. It's why in C you can't call a function above the code that defines it unless you have an explicit forward declaration that tells the compiler what it need to know to generate code for a call to the later function.

```
Syntax-directed translation is a structured
technique for building these all-at-once
compilers. You associate an action with each
piece of the grammar, usually one that
generates output code. Then, whenever the
parser matches that chunk of syntax, it
executes the action, building up the target
code one rule at a time.
```

#### Tree-Walk interpreters:
Some programming languages begin executing code right after parsing it to an AST(with maybe a bit of static analysis applied). to run the program, the interpreter traverses the syntax tree on branch and leaf at at time, evaluating each node as it goes.

This implementation style is common for student projects and little languages, but is not widely used for general-purpose languages since it tends to be slow.

Some people use "interpreter" to mean only these kinds of implementations, but others define that word more generally.


#### Transpilers:
Writing a complete back end for a language can be a lot of work, if you have some existing generic IR to target, you could bolt your front end onto that. Otherwise, it seems like you're stuck. But what if you treated some other source language as if it were an intermediate representation ?

You write a front end for your language. Then, in the backend, instead of doing all the work to <i>lower</i> semantics to some primitive target language, you produce a string of valid source code for some other target language that's about as high level as yours. Then you can use the existing compilation tool for <i>that</i> language as your escape route off the mountain and down to something you can execute.

they used to call this a <b>source-to-source compiler</b> or a <b>transcompiler</b> After the rise of languages that compile to JavaScript in order to run in the browser, they've affected the hipster sobriquet <b>transpiler</b>

#### Just-in-time compilation
This last one is less of a shortcut and more a dangerous alpine scrambled best reserved for experts. The fastest way to execute code is by compiling it to machine code, but you might not know what architecture your end user's machine supports. What to do ?

You can do the same thing that the HotSpot JVM, Microsoft's CLR and most JavaScript interpreters do. On the end user's machine, when the program is loaded --either from source in the case of js or platform-independent bytecode for the JVM and CLR --you can compile it natively for the architecture their computer supports. Naturally enough this is call <b>just-in-time compilation</b>. Most hackers just say <b>JIT</b>, pronounced like it rhymes with "fit".

The most sophisticated JITs insert profiling hooks into the generated code to see which regions are most performance critical and what kind of data is flowing through them. Then, over time, they will automatically recompile those hot spots with more advanced optimizations. 
```
This is, of course exactly where the HotSpots JVM gets its name.
```


## Compilers and Interpreters :
"What's the difference between a compiler and an interpreter?"

It turns out this is like asking the difference between a fruit and a vegetable. That seems like a binary either-or choice, but actually "fruit" is  <i>botanical</i> term and <i>vegetable</i> is culinary. One does not strictly imply the negation of the other. There are fruits that aren't vegetables(apples) and vegetables that are not fruits(carrots), but also edible plants are both fruits and vegetables, like tomatoes.

so back to Languages
- <b>Compiling</b> is an <i>implementation</i> technique that involves translating a source language to some other --usually lower-level --form. When you generate bytecode or machine code, you are compiling. When you transpile to another hight-level language you are compiling too.
- When we say a language implementation "is a <b>compiler</b>", we mean it translates source code to some other form but doesn't exeucte it. The user has to take the resulting output and run it themselves.
- conversely, when we say an implementation "is an <b>interpreter</b>, we mean it takes in source code and executes it immediately. It runs the program "from source".

But what about CPython? When you run your python program using it, the code is parsed and converted to an internal bytecode format, which is then executed inside the VM. From the user's perspective, this is clearly an interpreter --they run their program from source. But if you look under CPython's scaly skin, you'll see that there is definitely some compiling going on. 

The answer is that it's both. CPython is an interpreter, and it has a compiler in practise. Most scripting languages work this way.![[Pasted image 20230901132700.png]]
```
The Go tool is even more of a horticultural
curiosity. If you run go build , it compiles
your Go source code to machine code and
stops. If you type go run , it does that then
immediately executes the generated
executable.
So go is a compiler (you can use it as a tool to
compile code without running it), is an
interpreter (you can invoke it to immediately
run a program from source), and also has a
compiler (when you use it as an interpreter, it
is still compiling internally).
```

### Automatic Memory Management
There are two main techniques for managing memory: <b>reference counting</b> and <b>tracing garbage collection</b> (usually just called <b>"garbage collection"</b> or <b>"GC"</b>). Ref counters are much simpler to implement --I think that's why Perl, PHP, and Python started out using them. But overtime the limitations of ref counting become too troublesome. All of those languages eventually ended up adding a full tracing Gc or least enought of one to clean up object cycles

Tracing garbage collections has a fearsome reputation. It is a little harrowing working at the level of raw memory. Debugging a GC can sometimes leave you seeing hex dumps in your dreams. But remember, this journey is about dispelling magic and slaying those monsters, so we are going to write our own garbage collector.