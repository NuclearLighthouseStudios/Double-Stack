# Double Stack Distortion

These are the KiCAD schematics and board layout filed for my Double Stack Distortion pedal.  
If you just want the Gerber files or a PDF of the schematic check out the releases tab for downloads.

This PCB should be easily manufacturable with most online PCB houses by just uploading the gerber files.

This board is designed to be used with my Switchboard Pedal IO PCB which you can find [here](https://github.com/NuclearLighthouseStudios/Switchboard).

## BOM

| Reference     | Quantity | Value  | Description                                          |
| :------------ | -------: | -----: | :--------------------------------------------------- |
| C1 C7 C8      | 3        | 100n   | WIMA MKS2 63V                                        |
| C2 C4 C5      | 3        | 470n   | WIMA MKS2 63V                                        |
| C3 C6 C10     | 3        | 1µ     | WIMA MKS2 63V                                        |
| C9            | 1        | 1n     | WIMA MKS2 63V                                        |
| D1 D2 D3 D4   | 4        | 1N4148 | DO-35 Diode                                          |
| J1            | 1        |        | Pin Header, 6 pins, 2.54mm spacing                   |
| J2            | 1        |        | DC Barrel Jack with internal switch                  |
| Q1 Q2 Q3 Q4   | 4        | BC547B | 0.1A Ic, 45V Vce, Small Signal NPN Transistor, TO-92 |
| R1 R2 R11 R12 | 4        | 1M     | Metal film resistor 1%, DIN 0207                     |
| R10           | 1        | 390k   | Metal film resistor 1%, DIN 0207                     |
| R3 R7 R9 R13  | 4        | 10k    | Metal film resistor 1%, DIN 0207                     |
| R4            | 1        | 4.7k   | Metal film resistor 1%, DIN 0207                     |
| R5 R8         | 2        | 100k   | Metal film resistor 1%, DIN 0207                     |
| R6 R14        | 2        | 39k    | Metal film resistor 1%, DIN 0207                     |
| RV1 RV2       | 2        | 100k   | Alps RK09K1130C94 Potentiometer                      |
