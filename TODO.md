# Instruction Types to Differentiate by Color
- mov
- basic ALU
    - add/sub
- complex ALU
    - mul/div
- memory
    - ldr/str, adr
- branching
    - cmp, b, bl, br
- svc

# Instructions to implement:
- floating point
    - fmov
    - fcmp
    - fmul
    - fsub
    - fdiv

# Spice up Colors For
- .globl/.global, .text, .data, .bss
- special registers
    - x0 to x7 (procedure arguments and return values)
    - x9 to x14 (temporary)
    - x19 to x27 (callee-saved - aren't overwritten by procedures)
    - xzr, xr/x8 (syscall), pc/x15, ip0/x16, ip1/x17, pr/x18, sp/x28, fp/x29, lr/x30
- procedures called with bl (bl printf)
- _start
