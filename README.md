# Awesome-Agon-Light
Community maintained links to Agon Light resources. Feel free to add with a pull request ... please keep the same format for readability.

# OFFICIAL RESOURCES
### OFFICIAL Agon Light resources
- [ Agon Light Homepage - The Byte Attic](https://www.thebyteattic.com/p/agon.html)
- [Agon Light GitHub repo (design files, microSD card files, 3rd party docs etc](https://github.com/TheByteAttic/AgonLight)
- [Agon BBC Basic - OFFICIAL BBC Basic port](https://github.com/breakintoprogram/agon-bbc-basic)
- [Konami's King's Valley ported](https://youtu.be/oVHdhVJTzRo)
- [Olimex Argon Light 2 GitHub page](https://github.com/OLIMEX/AgonLight2)
- [MOS](https://github.com/breakintoprogram/agon-mos)

### Official Videos - The Byte Attic
- [Demonstrating Agon light™'s gaming capabilities and new hardware on sale for $50!](https://www.youtube.com/watch?v=KWRallh_hfc)
- [A first look at Agon Console 8](https://youtu.be/3NqbouGTTqs)

# Youtube videos
- [Simple Debugging on the Agon Light](https://www.youtube.com/watch?v=bAlpbd9ermk)
- [Agon Light 2 - a Z80 based SBC](https://www.youtube.com/watch?v=mlVW3eiqYis)
- [Is this the FASTEST and CHEAPEST 8-Bit Computer Ever?](https://youtu.be/CQ_C_RvJJ9A)
- 
- 

# Games for Agon Light
- [Pizza Dash](https://github.com/NicholasPratt/Pizza-Dash)
- [Space Safari by Nicholas Pratt](https://github.com/NicholasPratt/Space-Safari-)
- [Nova Star by Nicholas Pratt](https://github.com/NicholasPratt/Nova-Star)
- [ASCII Generator](https://github.com/NicholasPratt/BBCASCIIGENERATOR)
- [Sokoban](https://github.com/envenomator/agon-sokoban)
  

# BBC BASIC Resources
- [R.T.Russell - The home of BBC BASIC](http://bbcbasic.uk/)
- [A Short History of BBC Basic](http://bbcbasic.uk/bbcbasic/history.html)
- [An Introduction to Programming BBC BASIC By Peter Nairn](http://bbcbasic.uk/bbcwin/tutorial/index.html) 

# CP/M Resources
- [Nirash's CP/M port for Agon Light](https://github.com/nihirash/Agon-CPM2.2)

# Agon Light Emulator
- [Agon Light Emulator for Linux & Windows](https://github.com/tomm/fab-agon-emulator)

# Agon Light Technical
- [VDP Commands](https://github.com/breakintoprogram/agon-vdp/tree/main)



eZ80 Heaven
TASM Manual
MOS Information and Memory Map
MOS API
- [Learn eZ80 Assembly](https://www.chibiakumas.com/ez80/)
- [Zilog eZ80 Manual](https://github.com/iandstanley/Agon-Light-2/blob/main/docs/Zilog%20ez80%20processor.pdf)

# Technical Documentation
### Agon
- [Byte Attic: The Agon Light](https://www.thebyteattic.com/p/agon.html)
- [Break Into Program: Agon](http://www.breakintoprogram.co.uk/hardware/computers/agon)

### Updating Firmware
- [Updating Firmware](https://github.com/breakintoprogram/agon-docs/wiki/Updating-Firmware)

### Assembly
- [Agon Light Assembly](https://github.com/schur/Agon-Light-Assembly)

### GPIO 
- [GPIO](https://github.com/breakintoprogram/agon-docs/wiki/GPIO)

### BBC BASIC
- [BBC BASIC for Agon Manual](https://oldpatientsea.github.io/agon-bbc-basic-manual/0.1/index.html)
- [BBC Basic for Agon](https://github.com/breakintoprogram/agon-docs/wiki/BBC-BASIC-for-Agon)

### Libraries
- [FabGL](http://www.fabglib.org/index.html)
- [FatFS](http://elm-chan.org/fsw/ff/00index_e.html)

### Zilog
eZ80F92 Documentation
- [eZ80 CPU](http://www.zilog.com/docs/um0077.pdf)
- [Specification](https://www.zilog.com/docs/ez80/ps0130.pdf)
- [Calling C Functions from Assembly and Vice Versa](https://www.zilog.com/docs/appnotes/an0333.pdf)
- [ZDSII User Manual](http://www.zilog.com/docs/devtools/um0144.pdf)
- [EZ80 Heaven](https://ez80.readthedocs.io/en/latest/)

# Sample Applications and Templates
- [Agon Project templates](https://github.com/breakintoprogram/agon-docs/wiki/Projects)
### Application Templates
There are three template projects that can be used as a basis for your projects:
- A 16-bit mode Hello World app in assembler that demonstrates calling the MOS from a 64K segment in Z80 mode
- A 24-bit mode Hello World app in assembler
- A 24-bit mode Hello World app in C
All three apps act as MOS extensions; the resultant binary can be copied into the mos folder on the SD card, can be executed as a star command, and will display any passed parameters.

### The Applications
- A memory dump application written as a 16-bit mode assembly language app.
- An eZ80 disassembler written as a C application.
Both can be run as star commands from MOS.

# Agon Light Firmware
What is the Quark Firmware? The Quark firmware is the official operating system for the Agon Light. It consists of three main components:
- [MOS: Machine Operating System](https://github.com/breakintoprogram/agon-docs/wiki/MOS)
- [VDP: Visual Display Processor](https://github.com/breakintoprogram/agon-docs/wiki/VDP)
- [BBC BASIC for Agon: A specially adapted port of R.T.Russell's excellent BASIC interpreter](https://github.com/breakintoprogram/agon-docs/wiki/BBC-BASIC-for-Agon)

# Utilities
- [Agon-flash Flash Upgrader](https://github.com/envenomator/agon-flash)
- [Hex Loader, hex load over serial port](https://github.com/envenomator/agon-hexload)
- [agon-ez80asm, a fully featured EZ80 Assembler running on the Agon](https://github.com/envenomator/agon-ez80asm)
- [Agon Forth](https://github.com/lennart-benschop/agon-forth)
- [Agon Utilties](https://github.com/lennart-benschop/agon-utilities)

A utility to flash a MOS image to the eZ80F92 Flash without a ZDS USB cable
# Buying an Agon Light
Where can I buy one? At time of writing there are six official distributers of the Agon Light:
- [Mouser](https://www.mouser.com/ProductDetail/Olimex-Ltd/AgonLight2?qs=9vOqFld9vZWAIti5ng59Vw%3D%3D)
- [The Pi Hut](https://thepihut.com/products/agonlight2-z80-bbc-basic-retro-single-board-computer)
- [Olimex Ltd](https://www.olimex.com/Products/Retro-Computers/AgonLight2/open-source-hardware)
- [PCBWay](https://www.pcbway.com/project/gifts_detail/Agon_light_3f7ffaa8.html)
- [Agon Light Australia](https://agonlight.au/)
- [Agon Light Store (UK)](http://agon-light.store/)
