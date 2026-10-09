# Laser Diode Drivers

Three laser driver circuit designs, from basic constant-current operation to faster analog modulation.

| Design | Description |
|---|---|
| [01 — LM317 Driver](01-LM317-Driver/) | Basic constant-current laser diode driver |
| [02 — Op-Amp + MOSFET Driver](02-OpAmp-MOSFET-Driver/) | Adjustable analog current driver |
| [03 — LMH13000 Driver](03-LMH13000-Driver/) | High-speed analog laser diode driver |

Each design has its own **KiCad/** project folder, **BOM.csv**, and **Images/** folder.

## Status
Repository structure and documentation templates are set up. Actual KiCad design files, parts lists, images, and test measurements must be added and reviewed individually. Do not treat the templates as validated design data.

## Safety
Laser light can cause permanent eye damage. Use wavelength- and power-appropriate laser protection, controlled test setups, beam enclosures, and interlocks. Before connecting an expensive or dangerous laser diode, validate the circuit's start-up, shut-down, and modulation behavior into a suitable dummy load.

## License
No license has been selected yet. Add an appropriate hardware and documentation license before inviting reuse.
