This repo contains basic started code to use bluepill with VScode.
STM32F103C8T6 is used as the microcontroller. Do not flash to anyother microcontroller without making neccessary changes in Makefile and c_cpp_properties.json.

Needed libs below:

- GCC cross compiler: https://developer.arm.com/tools-and-s...
- Make for Windows: http://gnuwin32.sourceforge.net/packa...
- Recent OpenOCD builds: https://gnutoolchains.com/arm-eabi/op...
- Git: https://git-scm.com/

Get these and put the bin folders of them to your PATH. Create separate ENVVAR for arm gcc compiler called ARMGCC_DIR

Then you can use the following commands:
make
make clean
make flash
