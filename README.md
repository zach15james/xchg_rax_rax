this is a collection of work through two of xorpd's challenges:
- xchg rax, rax asm, math, & logic puzzles (first complete set online as far as I know)
- ReversingHero challenge solutions

For xchg rax, rax, the code I did run (for convenience or tedious necesssity is all inside asm, along w/ my .gdb - which may have been modified for specific exercises)
the command I ran was
```bash
nasm -f elf64 -g -F dwarf 0xNN.asm -o 0xNN.o && ld 0xNN.o -o 0xNN && gdb ./0xNN
```
