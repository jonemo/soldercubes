Soldercube Solidworks Models
============================

The files in this folder and its subfolders were used to develop the mechanical design of the Soldercube module types. All components including fabricated and purchased ones but excluding wires and fasteners are represented in these files. The level of detail varies depending on the type of object modeled: Purchased parts are only modeled to the level of detail required for modelling the assembly, while 3d printed parts for example are modeled such that they can be fabricated from the model.

### File Descriptions

Assemblies:

 * `Actuation Module.SLDASM` Solidworks Assembly file for Soldercube Actuation Module (with one actuated degree of freedom)
 * `Energy Module.SLDASM` Solidworks Assembly file for Soldercube Energy Module (rechargeable battery module)
 * `Structural Module.SLDASM` Solidworks Assembly file for the Soldercube Structural Module (passive module with neither actuator nor batteries)

Components

 * `Battery` contains simple representation of the dimensions of the rechargeable cell used in the Soldercube Energy module
 * `Circuit Boards` contains simplified geometrical representations of various printed circuit boards, used primarily to detect collissions during the design phase
 * `Cube Shell` contains the model used to generate STL files for both parts of the cube shell
 * `Dynamixel AX12` contains simplified geometrical representations of some internal components of the Dynamixel AX-12A servo motor (see also `Potentiometer`)
 * `Internal Gear` contains the model used to generate an STL file for the internal gear used in the Soldercube Actuation module
 * `Magnets` contains a very simple model of the magnets embedded in the module shell
 * `Potentiometer` contains a simplified geometrical representation of the potentiometer internal to the Dynamixel AX-12A servo motor as well as models used to generate STL models for the gears that attach to it in the Soldercube Actuation module
 * `Shafts and Pins` contains simple geometrical models of various pins used in Soldercube modules
 * `Slip Ring` contains a simplified geometrical representation of the Moog SRA-73540 slip ring, with and without the outer plastic enclosure

### How to use the files

All files in this folder were generated with Solidworks 2010 Service Pack 2.1 (64bit edition) and are saved in Solidwork's native file formats `.sldprt` and `.sldasm`. You will not be able to open these files with older versions of Solidworks. [eDrawings Viewer](http://www.edrawingsviewer.com/ed/solidworks-viewer.htm) is a free software for Windows and MacOS X that allows viewing (but not editing) Solidworks files.
