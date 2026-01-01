# CBU Replacement Daughterboard

This is the satellite PCB that houses the ESP32-C6 microcontroller module and connects to the drop-in replacement board.

## Project Files

- `CBU-Replacement-Daughterboard.kicad_pcb` - PCB layout
- `CBU-Replacement-Daughterboard.kicad_sch` - Schematic
- `CBU-Replacement-Daughterboard.kicad_pro` - KiCad project file

## Manufacturing Files

- **jlcpcb/gerber/** - Gerber files ready for PCB fabrication
- **jlcpcb/production_files/** - BOM and CPL files for assembly services

## Design Features

- Hosts the ESP32-C6 module
- Connects to the drop-in board via cable
- Designed to fit in a 3D-printed enclosure
- Allows for easier ESP32 placement and future module upgrades

## Assembly

This board requires:
1. ESP32-C6 module to be soldered
2. Connector to mate with the drop-in board cable
3. Optional: 3D-printed enclosure for protection and mounting
