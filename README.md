# ICE-DIP

Designed by Frank van den Hoef in 2021.

This is a small FPGA board containing the Lattice iCE40 UltraPlus 5K FPGA. 

## Features
- Lattice ICE40UP5K-SG48I FPGA, 5K logic elements, 15KB+128KB embedded block RAM
- DIP40 form factor with machined pin headers for easy integration in retro computer designs.
- Level translating bus switches on all I/O pins to allow interfacing with 5V logic. (NOTE: output levels will still be max 3.3V)
- 2MB SPI flash for 1 to 4 configuration images.
- On-board crystal oscillator.
- On-board power supplies for 3.3V and 1.2V.
- Open-source hardware. [Schematic](pcb/ice-dip-schematic.pdf) and layout (in KiCad format) are free for you to use and modify.

## Renders
<img height="500px" src="img/ICE-DIP front.png"> <img height="500px" src="img/ICE-DIP back.png">
