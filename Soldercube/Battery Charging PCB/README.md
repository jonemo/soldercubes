Battery Charging PCB
====================

### The Soldercubes Energy Module

The Soldercubes Engery Module contains three rechargeable batteries in the space that is occupied by the DC motor in the actuated Soldercube module. The Energy Module provides energy to all other connected Soldercubes when no external power is applied to the assembly, or charges its internal batteries when an external power supply is present.

Most use cases for the Energy Module are experiments with mobile Soldercube away from the Experiment Substrate. You can also embed an Energy Module in a Soldercubes assembly to bridge an unreliable power connection.

### The Battery Charging PCB

The printed circuit board (PCB) in this folder serves a dual purpose as one side of the battery holder that holds the three batteries in place, and as the control circuit that manages power into and out of the rechargeable batteries. The workhorse of the board is the Texas Instruments chip (part no `BQ24105RHLR`) which, at the time of designing this, was one of the few battery charge controllers that support charging of multiple LiPO4 cells in series. All other components on the board are peripherals to this "fully integrated" charge controller. In addition, two LEDs serve as indicators of the charging status. Pink and blue were chosen somewhat arbitrarily to not overlap with the green and red indicator LEDs of the main controller board in the Soldercube module.

### File Descriptions

 * `ChargerBottomv2.sch` EagleCAD schematic file, created using EagleCAD version 5.12
 * `ChargerBottomv2.brd` EagleCAD board layout file, created using EagleCAD version 5.12
 * `DFM Files` contains Gerber files for ordering stencils exported from the above design files. You would send these to your stencil cutting service if you plan to assemble these boards yourself. Note that the `.bsp` file is empty because there are no components on the underside of the board. Also note that some of the shapes were tweaked manually after exporting from EagleCAD.
