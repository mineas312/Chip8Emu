# Chip8Emu
CHIP-8 Emulator written in C

# Structure
1.  4KB RAM
2. 16 levels of 16bit stack
3. 8-bit registers
4. 16bit index register
5. HEX keyboard
6. Display 64x32
7. Audio output

More details on page: https://en.wikipedia.org/wiki/CHIP-8

# How to compile
Project can be compiled on Linux systems. It should compile on Windows but it was not tested.
To compile code you will have to download SDL2 and SDL2 libs from your distribution.
An example how to do this on Ubuntu:
`apt-get install libsdl2-dev`
`apt-get install libsdl2-mixer-dev`

GCC compiler is required.

After you have all needed stuff, go to project folder and run:
`sh build-linux.sh`

After the successful compilation, binary file should be in **bin** folder.
