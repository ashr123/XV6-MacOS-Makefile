# XV6-MacOS-Makefile
Small change to XV6's makefile to work on MacOS

## preparing XV6 for working on MacOS:

1. Install xCode and agree the terms of use.
2. Download xv6 from https://github.com/mit-pdos/xv6-public.
3. Install MacPorts from https://www.macports.org/.
4. Open a terminal window where you've downloaded the XV6.
5. Install Qemu by excecuting `sudo port install qemu i386-elf-gcc gdb`.
6. Replace the existing Makefile to [mine](Makefile).

In order to run, excecute in the terminal window `make qemu clean`.
