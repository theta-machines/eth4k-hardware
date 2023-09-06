# Disco Board &ndash; ETH4K
The [Disco Board &ndash; ETH4K](https://www.thetamachines.com/shop/eth4k/) is a completely open-source FPGA development board based on the iCE40HX4K. The board includes several robust communication methods such as Ethernet, USB, and abundant GPIO.

The iCE40HX4K features 3,520 logic cells, 80k-bits of embedded RAM, and 2 PLLs. The official tools for working with this device are [iCEcube2 Design Software](https://www.latticesemi.com/iCEcube2) and [Diamond Programmer](https://www.latticesemi.com/programmer). iCEcube2 is used to generate the bitmaps, and Diamond Programmer is used to flash the bitmaps onto the FPGA.

## Documentation
* [Pinout Diagram](https://www.thetamachines.com/downloads/hardware/eth4k-pinout.png)
* [Data Sheet](https://www.thetamachines.com/downloads/hardware/eth4k-data-sheet.pdf)
* [Schematic](https://www.thetamachines.com/downloads/hardware/eth4k-schematic.pdf)
* [Bill of Materials](https://www.thetamachines.com/downloads/hardware/eth4k-bom.pdf)

## KiCad Project Overview

* This PCB was designed using **KiCad 7** and its standard library of footprints/symbols/models.

* The project can be opened via the `ETH4K.kicad_pro` file.

* All custom footprints/symbols/models are located in the `project-library` directory. The same directory houses the schematic page template. 
