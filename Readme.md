A few years ago I made my first Amiga 1200 mechanical keyboard. I did not know at the time about any other efforts that might be underway so I just went ahead and did it. It turned out well and a lot of people built them. Still, there is always a temptation to try and improve something. I was never really happy about the mounting system and the 9U spacebar was a problem, even more so than finding the keycaps that match the Amiga key sizes because modern keyboards went in a different direction.

So here is version 2. At the time of the last keyboard, low-profile keyswitches existed but were hard to find and often could not use MX-stem caps, now it is easier. I'm typing this with a Nuphy Air75 v2 with "Gateron x Nuphy Moss" KS-33 switches and the feel is amazing. There is a lighter variant "Wisteria" and a regular brown tactile option. Blue (clicky) and several variants of linear including red are available too. These switches use a different footprint to standard MX so the PCB had to be redone.

The low profile switches do not come in a 5-pin PCB mount version so a plate is essential. While laser-cut would be amazing I don't have a laser cutter, also that would not be 3-dimensional and would not leave space for the stabilizer wires. To keep it printable on common 3D printers there are multiple pieces to print. I have used eSun matte PLA, a good opaque material that is a good match for an A1200.net case in white or black. The stabilizers mount to the plates, the holes in the PCB underneath are only for clearance. These plates keep the keyswitches perfectly straight during assembly, improve keyboard stiffness, dampen sound and make for a better appearance.

Under the old keyboard a 10x3mm aluminium bar was used to stiffen the whole assembly, running from one side of the case to another sitting on 3d-printed mounts. I want to move that out of the way of expansions under the keyboard. I never noticed a problem with a TF1230 but with a larger accelerator having a heatsink it might be. There is plenty of room for a PiStorm32-lite, by far the fastest and most cost-effective accelerator today.

One thing that hasn't been done is to source a Caps Lock key with a window for the LED. The LED mount is still there and you can put a LED under the switch but I don't know where you can get a windowed keycap for it. The LED section of this keyboard includes a circuit where it will light an alternate LED for power when Caps Lock is active. My keybaord has a green LED for power but that changes to blue when Caps Lock is activated.

If you don't want to use the LED function of this keyboard you can just snip away the top right of the PCB and use the original Amiga 1200 LED PCB. In that case don't bother with LEDs, capacitor, resistors or the inverter chip.

Requirements:
- one PCB (see the 'fab' folder for gerber files, ready to build)
- 96 Gateron KS-33 keyswitches
- 5 Gateron 2U plate-mount low-profile stabilizers
- 1 more Gateron low-profile stabilizer to disassemble - bend your own wire from 1.0mm music wire, available from hobby stores.
- 0805 LEDs: red, green, yellow/orange and blue (or whatever colors you like for the various functions)
- 0805 current-limiting resistor for each LED. Choose a value not less than 300 ohms. If your LEDs are too bright you can use higher values. I found that 500-1k ohms is fine. Your LEDs may vary.
- 0.1uF 0805 decoupling capacitor
- SN74LVC2G04DBVR dual inverter (available Mouser electronics)
- 5-pin dupont housing, pins and ribbon cable to connect LED section to Amiga
- one FFC connector, 32-way RA 1.25mm pitch. Molex 52044-3245 (available Mouser Electronics) or look on AliExpress.
- one FFC ribbon cable, 31-way. Cut one connector from Molex 15168-0400 (available Mouser Electronics) or look on AliExpress.
- Printed left and right plates to house stabilizers and switches on top of PCB (STLs in 3dprint folder)
- Printed left, right and bottom mounts to secure the keyboard in your case (STLs in 3dprint folder)
- various M3 bolts or plastic rivets for assembly
- 96 Amiga keycaps: user Steveed on Amibay recently sorted this out with Signature Plastics and they are perfect. Seems expensive? Not until you spend hours looking for and buying various sets and never end up with a full set. 
 
The cost of all this varies with the cost of PCB manufacture, keyswitches and stabilizers and of course the keycaps. As a very rough guide expect to pay *no less* than about:
- PCB $20
- keyswitches $40
- stabilizers $20
- LEDs and other components $2
- FFC connector and cable $8
- 3D printed parts $10

And assembly will take at least three hours. That's just under $100 in parts alone and does not even count a quality set of keycaps at around $150. (But if you weren't slightly obsessed you probably wouldn't have an Amiga in 2024.)

The license for this keyboard is non-commercial. However if a person has ordered the minimum of 5 PCBs from one of the usual places and wants to offer the extras for sale at near cost that is reasonable.

Thanks to Steveed (Amibay) and to everyone that has supported this project. 

License: CC-BY-NC-SA 4.0