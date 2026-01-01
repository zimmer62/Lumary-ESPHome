# CBU Drop-in Replacement PCB

This is the main drop-in replacement PCB for the original Lumary CBU (Control Board Unit).

## Project Files

**Note**: The files in this directory are named "LearningTest2" - this was the working project name during development. These files represent the final design for the CBU replacement PCB.

- `LearningTest2.kicad_pcb` - PCB layout
- `LearningTest2.kicad_sch` - Schematic
- `LearningTest2.kicad_pro` - KiCad project file

## Manufacturing Files

- **jlcpcb/gerber/** - Gerber files ready for PCB fabrication
- **jlcpcb/production_files/** - BOM and CPL files for assembly services

## Design Features

- Drop-in replacement for original CBU board
- Maintains original connector pinouts and form factor
- Designed for easy installation without rewiring
- Connects to ESP32-C6 daughterboard via cable

## Library

The `Library.pretty/` folder contains custom footprints used in this design, including the CBU footprint that matches the original board dimensions.
