# LMH13000 Laser Diode Driver

Analog laser diode driver based on LMH13000.

## Design specifications
| Parameter | Value |
|---|---|
| VLD Supply voltage | To be documented |
| Driver PWR voltage | 3.3-5V |
| DAC input range | 0-2V |
| Laser current range, Low Setting | Low: 5mA - 1A |
| Laser current range, High Setting* | Low: 250mA - 5A |
| Signal voltage | 3.3V |
| Rise Time | Not documented yet |

*High power setting not tested - use with caution and only in short bursts/low duty cycle.

## Contents
- **KiCad/** — KiCad project, schematic, and PCB files
- **BOM.csv** — bill of materials
- **Images/** — schematic exports, PCB renders, and board photos

## Build notes
Coming soon....

## Safety
Verify maximum current, transient behavior and output polarity into a dummy load before attaching a laser diode. Use appropriate eye protection and safe beam containment.
