# Sensing Boards

A collection of sensor and embedded boards designed in KiCad.

## Boards

### Hall-FX Module

An ESP32-S3-based Hall-effect sensing board built around the TI TMAG5273
magnetic sensor. The design also includes USB-C, battery and power-management
circuitry, status LEDs, pushbuttons, ESD protection, and supply decoupling.
I worked with [Johann Samuel Nana](https://www.linkedin.com/in/johann-s-nana/)
([GitHub](https://github.com/sam93502)) on the schematic capture.

- [KiCad project](hall-fx/HALL_module.kicad_pro)
- [Schematic](hall-fx/HALL_module.kicad_sch)
- [PCB layout](hall-fx/HALL_module.kicad_pcb)
- Custom footprints, symbol, and 3D models are in the [hall-fx directory](hall-fx/).

### ToF Sensor Module

A time-of-flight distance-sensing board using the ST VL53L0CX sensor. Its
schematic provides a 3.3 V supply, I2C connections, and an XSHUT control signal,
with ESD protection and decoupling. Designed for Penguin, the modules are
intended to be chained using their I2C input and output connections.

- [KiCad project](tof-module/TOF_module.kicad_pro)
- [Schematic](tof-module/TOF_module.kicad_sch)
- [PCB layout](tof-module/TOF_module.kicad_pcb)

## Working with the designs

Open each board's `.kicad_pro` file in KiCad to view or edit the project. Check
the corresponding schematic for connector pin assignments and electrical
requirements before connecting a board. The project directories also contain
`.zip` archives of the PCB files.

---
Jeevan Sanchez, 2026
