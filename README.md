# Acolyte6502Computer
Acolyte 6502 "Homebrew" Computer with VGA and PS/2 Keyboard support

The ZIP file contains everything needed.  "Rev2" is the latest version.

This is a "Homebrew" computer, running a W65C02 Microprocessor at 3.14 MHz.
It has 80K SRAM, and 128K FlashROM.  There is also 32K write-only memory for VGA output.
There are three video modes that it supports:

640x240 Monochrome

320x240 4-Color

160x240 16-Color

PS/2 Keyboard support built in, Genesis controller also supported.
Supports 'cassette' audio data input through a 3.5mm audio jack, and 1-voice square wave audio out through the same jack.
One SPI EEPROM is built into the board, as well as a socket for a MicroSD Card Adapter.
It is powered with 5V USB.

The goal is that this board would cost less than $100 to assemble.
There are also no CPLD or FPGA chips used, everything besides the 6502/6522/RAM/ROM are 74HC' logic chips.

The Rev2 software contains many programs such as: 
Scratchpad, RPN Calculator, Etch-A-Sketch, Music Composer, Assembler/Disassembler, Memory Dump, Memory Transfer GUI, and a simple Snake game.

More information can be found on the 6502.org Forum.
