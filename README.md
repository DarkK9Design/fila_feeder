# fila_feeder
An automatic filament feeder designed to simplify filament loading and unloading at the 3D printer toolhead using a Stealthburner toolhead board, a servo, and filament sensor to detect and feed filament to and from the toolhead. **DISCLAIMER:** It is still very much in beta. Read the comments on the [.CFG file](https://github.com/DarkK9Design/fila_feeder/blob/main/Macros/fila_feeder.cfg)

<img width="1255" height="994" alt="Screenshot 2026-10-03 144425" src="https://github.com/user-attachments/assets/b08d2e2e-a5ff-4781-ba02-2d7c5a9a04c9" />


# CANBus configuration help
https://canbus.esoterical.online/

# Files to print
- [[a]_Lever_0.6.stl](https://github.com/DarkK9Design/fila_feeder/blob/main/CAD/STLs/[a]_Lever_0.6.stl)
- [[a]_PCB_Mount_0.2.1.stl](https://github.com/DarkK9Design/fila_feeder/blob/main/CAD/STLs/[a]_PCB_Mount_0.2.1.stl)
- [[a]_Secure_Cap_0.3.stl](https://github.com/DarkK9Design/fila_feeder/blob/main/CAD/STLs/[a]_Secure_Cap_0.3.stl)
- [Main_Plate_0.6.stl](https://github.com/DarkK9Design/fila_feeder/blob/main/CAD/STLs/Main_Plate_0.6.stl)
- [Bowden_In_0.7.1.stl](https://github.com/DarkK9Design/fila_feeder/blob/main/CAD/STLs/Bowden_In_0.7.1.stl)

**All files** are located on this GitHub in the [STLs folder](https://github.com/DarkK9Design/fila_feeder/tree/main/CAD/STLs)

# Print settings
All files are to be printed using 'VORON Standard' parts settings/filaments:
| 3D Printing Process: Fused Deposition Modeling (FDM) | Infill Type: Grid, Gyroid, Honeycomb, Triangle or Cubic |
|------------------------------------------------------|---------------------------------------------------------|
| Material: ABS/ASA                                    | Infill Percentage: 40%                                  |
| Layer Height: 0.2mm                                  | Wall Count: 4                                           |
| Extrusion width: Forced 0.4mm                        | Solid Top/Bottom Layers: 5                              |
| x.x.1 Print files                                    | Print with Tree Supports                                |

# Bill of Materials
| Category:         | Part Description:                    | Qty: | Links                   | Notes                                                                  |
|-------------------|--------------------------------------|------|-------------------------|------------------------------------------------------------------------|
| Fasteners         |                                      |      |                         |                                                                        |
|                   | M3x8 SHCS                            |   10 | https://a.co/d/037f3WVD |                                                                        |
|                   | M3x8 FHCS                            |    1 | https://a.co/d/0hF9KEpC |                                                                        |
|                   | M3x20 SCHS                           |    1 | https://a.co/d/07LzdmIO |                                                                        |
|                   | M3x30 SCHS                           |    1 | https://a.co/d/07IOfGE3 |                                                                        |
|                   | M3 Heat Set Insert (M3x5x4)          |    8 | https://a.co/d/00ZfhXog |                                                                        |
|                   | M3 T-Nut                             |    3 | https://a.co/d/071vCX4D |                                                                        |
|                   | M2x12 SHCS                           |    2 | https://a.co/d/02RGdxsP |                                                                        |
| Motion            |                                      |      |                         |                                                                        |
|                   | BMG Drive Gear Kit                   |    1 | https://a.co/d/01gLroWM |                                                                        |
| Electronics       |                                      |      |                         |                                                                        |
|                   | Omron D2F-01F Micro Switch           |    1 | https://a.co/d/0jkQkVP9 |                                                                        |
|                   | NEMA17 Pancake Stepper Motor         |    1 | https://a.co/d/00Iv0LOb | Could use any NEMA 17 stepper                                          |
|                   | SB Toolhead Board                    |    1 | https://a.co/d/0isNCulj | Any similar board should work. Use the included connectors for cabling |
|                   | MG90S 9G Micro Servo                 |    1 | https://a.co/d/0gZUF8IG | Use the 21mm included arm                                              |
| Misc.             |                                      |      |                         |                                                                        |
|                   | 6x3mm Neodimium Magnet               |    2 | https://a.co/d/0f8KDar4 |                                                                        |
|                   | 4mm Threaded Bowden Coupler          |    2 | https://a.co/d/08kZ09dT |                                                                        |
|                   | Loctite Blue Threadlocker Stick      |    1 | https://a.co/d/00mKnUja |                                                                        |
|                   | PTFE Tube (4mm OD 2.5mm ID) - 1000mm |    1 | https://a.co/d/00Jn22YE |                                                                        |
|                   | PTFE Tube (4mm OD 2.5mm ID) - 50mm   |    1 | https://a.co/d/00Jn22YE |                                                                        |
|                   | 5mm steel ball-bearing               |    1 | https://a.co/d/0a5YDpLx |                                                                        |
