# Op-Amp + MOSFET Laser Diode Driver

![Analog laser driver PCB, top view](Images/Intermediate-Driver-PCB-Render-Top.png)

Analog current regulator using an op-amp, MOSFET, and current-sense resistor.

## Design specifications
| Parameter | Value |
|---|---|
| Supply voltage | 9-12V Recommended |
| Laser current range | Based on Current-Sense Resistor value |
| Modulation/control input | DAC pin: 0-5V |
| Rise time* | Not documented yet |

## Contents
- **KiCad/** — KiCad project, schematic, and PCB files
- **BOM.csv** — bill of materials
- **Images/** — schematic exports, PCB renders, and board photos

## Build notes
Coming soon

## Safety
Verify maximum current, transient behavior and output polarity into a dummy load before attaching a laser diode. Use appropriate eye protection and safe beam containment.
