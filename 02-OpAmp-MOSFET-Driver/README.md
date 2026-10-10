# Op-Amp + MOSFET Laser Diode Driver

![Analog laser driver PCB, top view](Images/Intermediate-Driver-PCB-Top.png)

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

## Testing
Do not exceed 12V for the main supply voltage. Start with 0V on the DAC input pin and gradually increase, measuring output current with a multimeter in series with the laser diode. Laser power is directly proportional to input voltage. Remember that the total current is equal to bias current plus current set by DAC. 
