# mellori_ITX
Mellori (Little Raven) - Small Form Factor printable case for AMD Raven Ridge systems

This project is nearing release but no files are available just yet. My appologies if you found this a bit too soon.

Description
-----------
The Mellori ITX case was designed to fill the need for a small form factor computer case for AMD-based systems and measures
less than 200x200mm at only 60mm high (plus feet). The little raven achieves this small size by combining several existing innovations.
First the AMD Raven Ridge CPU chips provide integrated graphics, allowing the system to omit a bulky graphics card to
reduce overall height. The back panel space where such a card would go is used for the power connector and button.
Next, by using Minibox PicoPSU power supply, a whole lot of space is saved while moving the bulk of the supply to a brick
outside the PC. Hard disk space is reduced by using an SSD. Finally by lowering the top of the case below the height
of the CPU cooling fan, that fan serves double duty cooling all components while providing an aethetically pleasing feature
on an otherwise non-descript small box. Vents on the bottom are located to force air past key components before exiting.

Board Considerations
--------------------
The Mellori_ITX is motherboard-specific due to the location of the cooling fan cutout. This is easily modified by changing
two dimmensions in the CAD files that specify the center of the cooling fan/heatsink relative to the back corner of the board.
The original design was for the Gigabyte AB350N Gamng WiFi motherboard which also includes programmable LED lighting along
the front of the board - the design includes vents that allow these lights to shine down on the desk in front of the computer.

3D Printing
-----------
Mellori is designed for easy 3D printing. It is small enough to print on a 200x200mm bed and can be printed with almost no
supports. Only the 4 small hex holes on the bottom need any support - the original prototype used thermal inserts for
board mounting, but small supports seem simpler for someone new to 3D printing so this is changing for version 1.

The case consists of 4 printed parts:
1) The base which includes vents and standoffs for mounting an ITX motherboard.
2) The back includes a cutout for standard ITX back panel and holes for a power connector and button.
3) The top which may require relocation of the fan cutout if another board is used (default is AB350N).
4) A fan grill for the AMD wraith-stealth cooler which only has a shroud and no grill to keep things out.

All of these parts are easy to print. A small test part is also included to verify your ability to print the supports
for the screws before wasting a lot of time and material on the whole thing.

The back panel is a simple extrusion, so changing it for a different power connector or button is easily done
using solvespace - the best free CAD program ever.

Pending release
---------------
I'll release the CAD and STL files after printing a test of the new base using threaded nuts instead of thermal inserts.
The design fits together well and my system is currently being used for designing and slicing the changes.
There are currently no features for securing the top to the base, but it stays on well enough. I'm sure we can design
something a little tighter soon enough.
