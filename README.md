# asm
evolution of my learning on asm 32bits and 64bits

For the a64.asm

```
1- nasm -f elf64 a64.asm -o a64.o
```
```
2- ld a64.o -o a64
```
```
3- ./a32
```


For the a32.asm 

```
1- nasm -f elf32 a32.asm -o a32.o
```
```
2- ld -m elf_i386 a32.o -o a32
```
```
3- ./a32
```
