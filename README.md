# LT1356-breakout-board
# Overview
The LT1356 is a quad-input op-amp with high slew rate, fast settling time, low input noise and a wide supply voltage range, making it a fantastic ADC driver for ADCs with +/- 10V swings. It's a great choice for projects that want to conserve board space, but still need a lot of inputs. [You can find the official documentation for the chip here.](https://www.analog.com/en/products/lt1356.html). This is a breakout board made in Kicad with dedicated headers for a power supply input and for input voltages. 

*_Note_*: The board is currently designed as a buffer amplifier. Make sure to edit the design if you want non-unity gain. A future update of the design will include a schematic setup for a non-inverting amplifier on each input. 

# Navigating this repo
The main folder contains relevant Kicad files (.pro, .pcb, .sch). The `gerber` directory has a PCB-fabrication ready set of gerber files. The `library` directory has a custom footprint (.kicad_mod) that works for the SOP version of this chip. The official Analog part file for the chip (.lib) can also be found there.

# Board images
PCB Layout:
![PCB Layout](https://i.imgur.com/PXVU5Lv.png)

Schematic:
![Schematic](https://i.imgur.com/40n2359.png)
