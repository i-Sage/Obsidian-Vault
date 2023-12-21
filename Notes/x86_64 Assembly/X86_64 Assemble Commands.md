2023-10-31  ---  10:06

___
# X86_64 Assembly Assemble commands (yasm assembler)
---
The appropriate **yasm** assembler command for reading the assembly language source file is as follows:
```sh
	yasm -g dwarf2 -f elf64 example.asm -l example.lst
```
 - The **-g dwarf2** option is used to inform the assembler to include debugging information in the final object file.
 - The **-f elf64** informs the assembler to create the object file in the **ELF64** format which is appropriate for the 64-bit Linux-based systems.
 - The **-l** informs the assembler to create a list file.

NOTE:
A list file shows the line number, the relative address, the machine language version of the instruction (including variable references), and the original source line. List files are very useful when debugging.
---

## Linker
The linker sometimes referred to as the linkage editor, will combine one or more object files into a single executable file. Additionally, any routines from user or system libraries are included as necessary. The GUN golden linker *ld* is used. The appropriate linker command are as follows:
```sh
ld -g -o example example.o
```
The -g option is used to inform the linker to include debugging information in the final executable file.
### References

---