## System Call
- A **system call**, or a **syscall**, is when a program requests a service from the kernal.
- System calls will differ by operating system because operating systems use different kernels.
- All syscalls have an ID associated with them (a number).
- Syscalls also take arguments, meaning, a list of inputs.

## Specific to the yasm assembler
## Program Format 
A properly formatted assembly source file consists of several main parts:

- Data section where initialized data is declared and defined.
- BSS section where uninitialized data is declared.
- Text section where code is placed.

## Comments
The semicolon (;) is used to note program comments.

## Numeric Values
Number values may be specified in decimal, hex, or Octal. 
- When specifiying in hex, the Numeric value is preceded with a 0x.
- When specifying octal, the Numeric value is preceded with a q.
- The default base is decimal,no special notation is required.

## Defining Constants
Constants are defined with **equ**. The general format is:
- <name>    equ    <value>
The value of a constant cannot be changed during program execution.

## Data Section
The initialized data must be declared in the "section .data" section. There must be a space after the world 'section'. All initialized variables and constants are placed in this section. Variable names must start with a letter, followed by letters or numbers, including some special characters (such as the underscore, "_"). Variable definitions must include the name, the data type, and the initial value for the Variable.
The general format is:
<variable_name>     <data_type>     <initialvalue>

The supported data types are as follows:

| Declaration |                      |
|-------------|----------------------|
| db            | 8-bit variable(s)               |
| dw            | 16-bit variable(s)              |
| dd            | 32-bit variable(s)              |
| dq            | 64-bit variable(s)              |
| ddq           | 128-bit variable(s) -> integer  |
| dt            | 128-bit variable(s) -> float    |

initialized arrays are defined with comma separated values.
```asm
arr     dd      100, 200, 300       ; 3 element array
```

## BSS Section
Uninitialized data is in the "section .bss" section. There must be a space after the word 'section'. All unitialized variables are declared in this section. Variable names start with a letter followed by letters or numbers including some special characters (such as the underscore). The general format is :
<variable_name>     <res_type>      <count>

The supported Data types are as follows:

| Declaration |                     |
|------------ | ------------------- |
| resb        | 8-bit variable(s)   |
| resw        | 16-bit variable(s)  |
| resd        | 32-bit variable(s)  |
| resq        | 64-bit variable(s)  |
| resdq       | 128-bit variable(s) |

b_arr       resb        10              ; 10 element byte array
...
q_arr       resq        200             ; 200 element quad array

## Text Section
The code is placed in the "section .text" section. There must be a space after the word 'section'. The instructions are specified one per line and each must be a valid instruction with the appropriate operands.

The text section will include some headers or labels that define the initial program entry point. For example, assuming a basic program using the standard system linker, the following declarations must be included,

```asm
global _start
_start:
```

No Special label or directives are required to terminate the program. However, a system service should be used to inform the operating system that the program should be terminated and the resources, such as memory, recovered and re-utilized.
<br>

## Labels:
A "label" is used to label a part of code. Upon compilation, the compiler will calculate the location in which the label will sit in memory. Any time the name of the label is used afterwards, that name is replaced by the location in memory by the assembler.
<br>

## The "Start" Label:
The "_start" label is essential for all programs. When you program is assembled and later executed, it is executed first at the location of "_start". If the linker cannot find "_start", it will throw an error.
