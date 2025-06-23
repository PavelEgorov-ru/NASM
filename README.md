Изучение ассемблера

1. установить nasm `sudo apt install nasm`
2. установить отладчик gdb `sudo apt install gdb`
3. установить настройки отображения кода ассемблера с синтаксисом 
intel в файле .gdbinit `echo "set disassembly-flavor intel" > ~/.gdbinit`
4. скомпилировать исходный код `nasm -f -elf -o first.o first.asm`
5. линкер `ld -m elf_i386 -o first first.o`
6. запустить программу `./first`
