this is a collection of all the completed solutions to the xorpd xchg rax, rax {asm,math,logic} challenge set

For the 'dynamically-analyzied' ie emperically-solved solutions, I did run:
```bash
nasm -f elf64 -g -F dwarf 0xNN.asm -o 0xNN.o && ld 0xNN.o -o 0xNN && gdb ./0xNN
```
