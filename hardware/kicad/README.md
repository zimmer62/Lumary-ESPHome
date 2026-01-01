# KiCad PCB Design Files

This directory contains KiCad project files for the Lumary ESPHome hardware modification.

## Projects

### CBU-Drop-in
Drop-in replacement PCB that replaces the original Lumary CBU (Control Board Unit). This board maintains the same form factor and connector pinouts as the original, allowing it to be installed without rewiring.

**Note**: The files are named "LearningTest2" as this was the working project name during development. These files represent the final CBU replacement PCB design.

### CBU-Replacement-Daughterboard
Satellite PCB that houses the ESP32-C6 module and connects to the drop-in board via a cable. This separation allows for easier ESP32 placement and future module upgrades.

## Manufacturing

Each project folder contains a `jlcpcb/` subdirectory with:
- `gerber/` - Gerber files for PCB manufacturing
- `production_files/` - BOM (Bill of Materials) and CPL (Component Placement List) for assembly

These files are ready to be uploaded to JLCPCB or other PCB manufacturers for production.
