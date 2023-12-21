2023-10-30  ---  11:06
___
A CPU register, or just a register, is a temporary storage or working location built into the CPU itself. Computations are typically performed by the CPU using registers.
## General Purpose Registers

There are sixteen, 64-bit general purpose registers GPRs. A GPR can be accessed in full, or by the lower 32, 16, and 8 bits.

|64-Bit Register|Lowest 32-Bits |Lowest 16-Bits|Lowest 8-Bits|
|-----|----|----|----|
| rax | eax| ax | al |
| rbx | ebx | bx | bl|
| rcx | ecx | cx | cl|
| rdx | edx | dx | dl|
| rsi | esi | si | sil|
| rdi | edi | di | dil|
| rbp | ebp | bp | bpl |
| rsp | esp | sp | spl |
| r8 | r8d | r8w | r8b |
| r9 | r9d | r9w | r9b |
| r10 | r10d | r10w | r10b |
| r11 | r11d | r11w | r11b |
| r12 | r12d | r12w | r12b |
| r13 | r13d | r13w | r13b |
| r14 | r14d | r14w | r14b |
| r15 | r15d | r15w | r15b |


![[X86_64 Registers.png]]
## NOTE: 
Some GPRs are used for dedicated purposes.
<br>
## Stack Pointer Register:
 The rsp register is used to point to the current top of the stack. The rsp register should not be used for data or other uses.
<br>
## Base Pointer Register:
 The rbp register is used as a base pointer during function calls. The rbp register should not be used for data or other purposes.
<br>
## Instruction Pointer Register:
 In addition to the GPRs, there is a special register, rip, which is used by the cpu to point to the next instruction to be executed.
<br>
## Flag Register (rFlag):
 The Flag resgister, rFlags, is used for status and cpu control information. The rFlag register is updated by the cpu after each instruction and is not directly accessed by programs. This register stores information about the instruction that was just executed.
<br>
## XMM Registers:
 There are a set of dedicated registers used to support 64-bit and 32-bit operations and single instruction multiple data (SIMD) instructions. The SIMD instructions allow a single instruction to be applied simultaneously to multiple data items. Used effectively, this can result in a significant performance increase. The XMM registers are:
 
 | 128-Bit Registers|
 |------------------|
 | xmm0 |
 | xmm1 |
 | xmm2 |
 | ...|
 | xmm15 |
<br>

## NOTE:
Some of the more recent x86_64 processors support 256-Bit xmm registers.



---
### References
---