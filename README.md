b1u3OS
====

This is my original OS(kernel only).
## Usage

`i686-elf-as boot.s -o boot.o`
`i686-elf-gcc -c kernel.c -o kernel.o -std=gnu99 -ffreestanding -O2 -Wall -Wextra`
`i686-elf-gcc -T linker.ld -o b1u3OS.bin -ffreestanding -O2 -nostdlib boot.o kernel.o -lgcc`


## Author

Yuma Noguchi(b1u3)
