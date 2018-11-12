Lecture 02 Labs
===
This is the labs files, please clone this repo.

## asm01
1. Under the path of **asm01**, use `make` to build

## asm02
1. Download the qemu pack [here](http://140.116.39.233/ese/02/gnu-mcu-eclipse-qemu.zip)
2. Extract into the **asm02** folder
3. Under the path of **asm02**, use `make` to build, and then `make qemu` to emulate
4. Use another terminal window to open gdb by command `arm-none-eabi-gdb`
5. Connect to qemu: `target remote 127.0.0.1:1234`