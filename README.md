Cerberus
========

Derivative of the Rostock 3D delta printer - 

[cc by sa 3.0]


Cerberus
========

2/19/2013

Cerberus is an experimental 3D Delta Robot printer that uses spectra filament for the vertical carriage drive system instead of traditional toothed belts. Please be aware that there will probably (and most likely) be significant changes and improvements made to this design. - A photo gallery of the Ceberus prototype can be found in the G+ gallery here: http://tinyurl.com/amwygs6

A BOM is being worked on and will be made available as a spreadsheet in the near future.

Print Files:

Qty - Filename

2 - AzteegX3 Controller Mount Bracket.stl

3 - Bottom Idler Bracket - Snap Fit.stl (requires two 4mm ID cnc machined v-groove idlers for each bracket 2x3=6)

3 - Glass Bed Mount Bracket.stl (for non-heated bed)

2 - LCD Mounting Bracket v1.stl - for Panucatt Viki

3 - Outer Brace Bottom Bracket.stl

3 - Outer Brace Upper Bracket.stl

1 - platform.stl

2 - Ramps 1.4 Controller Mount Bracket.stl

3 - Tripod Brace Bott with Motor Mount - for snap fit lower idler.stl

3 - Tripod Brace Top v2.stl

3 - Upper Idler Adjuster Body.stl

3 - Upper Idler -axle (airtripper).stl

3 - Upper Idler-Adjuster Saddle.stl - (requires 1 8mm ID cnc machined v-groove idler per saddle 1x3=3)

3 - Vert Carriage for 608 w roller.stl (requires 3 608 'w' cnc machined rollers with bearing per carriage 3x3=9)

3 - Vert carriage to arm effector bracket.stl

Experimental Files:

1 - platform - bed leveler.stl - for when Auto-z leveling is implemented in firmware

1 - Z-probe L bracket for Bed Leveler Platform - for Auto z-leveling. Not implemented

3 - Vert carriage for 623 Dual Bearing Roller - The cnc machined dual-623 delrin roller for this carriage is not yet widely available

Notes:

All machined parts required to build Cerberus are now all available for purchase at http://3d.grabercars.com. They are manufactured on a CNC lathe to very tight tolerances.

SPECTRA FILAMENT VERTICAL CARRIAGE DRIVE SYSTEM:
Cerberus does not use belts or leadscrews. It uses a very strong braided filament called spectra. This is commonly used as fishing line. Cerberus uses 65lb test line. The drive system requires a threaded 'spool' or 'drive reel' that grabs the spectra very securely. CNC machined delrin filament drive reels are now available for purchase at 3d.grabercars.com - It is not recommended to use 3D printed drive reels because the print accuracy of your printer will suffer.

LOWER FILAMENT GUIDE IDLERS:
Due to the high tension required of the spectra filament drive system, the lower filament idler assy requires two cnc machined delrin V-Groove idler filament bearings riding on a 4mm smooth shaft. These idlers transfer the horizontal movement of the filament from the stepper motors and Filament Drive Reel vertically into the t-slot of the extrusion

VERTICAL CARRIAGES:
The Cerberus vertical carriages move up and down the extrusion towers by rolling on 3 cnc machined delrin 'w' rollers per carriage. Each roller consists of a cnc machined delrin cover with a 608zz bearing pressed in. The roller rides in the T-Slot of the 1515-lite extrusion. This makes for a very smooth and accurate linear carriage system. 'w' Rollers and 608zz bearings can be purchased from 3d.grabercars.com


FILAMENT TENSION SYSTEM:
Due to the high tension required of the spectra filament drive, the upper idler adjuster bearing carrier requires one machined delrin V-Groove idler filament bearing per vertical tower, riding on an 8mm shaft. This upper idler bearing transfers the upward motion of the spectra filament at the top of the printer towers into downward motion. I used a printed 8mm idler bearing shaft borrowed from Airtrippers Bowden extruder (Search www.thingiverse.com) and manufactured the delrin V-Groove idlers with 8mm I.D. hole on a CNC lathe.

EXTRUDER:
For a .5mm nozzle Cerberus delta printer we recommend the excellent Airtripper's Bowden Extruder. http://airtripper.com/1071/airtrippers-bowden-extruder-v3-updated-design/. Direct drive filament extrusion requires a very powerful stepper motor. If you experience problems with the extruder stepper motor skipping steps, you probably aren't using a Kysan 1124090 Nema 17 Stepper Motor or you are trying to use a .35mm nozzle. Delta Robot 3D printers can achieve incredible print speeds, but your extrusion system must be able to cope with the filament volume. It is recommended to use a .5mm nozzle with a direct drive system or use a geared stepper extrusion design with 5:1 or 3:1 reduction ratio.

