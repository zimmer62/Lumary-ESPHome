# Hardware

This directory contains all hardware design files for the Lumary ESPHome project.

## Structure

- **kicad/** - PCB design files for the controller boards
  - **CBU-Drop-in/** - Drop-in replacement PCB for the original CBU
  - **CBU-Replacement-Daughterboard/** - Satellite board that holds the ESP32-C6 module
- **3d_models/** - 3D printable enclosure and mounting files

## Overview

The hardware modification consists of two PCBs:

1. **Drop-in Board**: Replaces the original CBU board directly, maintaining the same form factor and connector pinouts
2. **Daughterboard**: A separate board that houses the ESP32-C6 module and connects to the drop-in board

This two-board approach allows for easier assembly and future upgrades to the ESP32 module.
