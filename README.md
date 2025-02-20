# Metal Detector Project

This project provides a comprehensive reference for building a pulse induction metal detector. It includes the general system scheme, hardware design files, PCB designs, CAM files for manufacturing, and a USB to UART module for ESP32 integration.


## Overview
The Metal Detector project is designed to help enthusiasts and professionals understand and implement a pulse induction metal detector. The repository contains:

- General Scheme: Detailed system and hardware schematics.
- PCB Design Files: Ready-to-use designs for fabricating the circuit board.
- CAM Files: Files required for computer-aided manufacturing.
- ESP32 Integration: A USB to UART module for connecting the detector to an ESP32 microcontroller.
## Features
- Pulse Induction Operation: Implements the principles of pulse induction metal detection.
- Detailed Schematics: Complete general and hardware design documents.
- PCB and CAM Files: Design files for PCB manufacturing and assembly.
- ESP32 Interface: Provides a USB to UART bridge for interfacing with ESP32-based systems.
  
## Repository Structure

Metal_Dedector/
- ├── CAM file/              # CAM files for PCB manufacturing
- ├── PCB files/             # PCB design files and layouts
- ├── USB to UART for ESP32/  # Interface files for ESP32 integration
- ├── Metal Dedektör.drawio   # Schematic diagram created with draw.io
- ├── README.md              # This README file
- └── SECURITY.md            # Security policy information

## Getting Started

### Prerequisites

#### Electronics Knowledge:
- Basic understanding of electronics and PCB design.
#### Software Tools:
- Draw.io for viewing and editing schematics.
- PCB design software (such as Eagle or KiCad) for viewing the PCB files.
- A computer with a USB interface for using the ESP32 integration module.
### Installation
#### Clone the Repository:
```git clone https://github.com/metevs09/Metal_Dedector.git```

#### Review the Design Files:
- Open Metal Dedektör.drawio with Draw.io to view the schematic.
- Check the PCB files in the PCB files/ directory.
- Refer to the files in USB to UART for ESP32/ for ESP32 interfacing details.
#### Manufacture and Assemble:
- Use the CAM files to prepare your PCB for manufacturing.
- Assemble the components following standard electronic assembly practices.
### Usage
Once the hardware is assembled:

1. Connect the ESP32 via the USB to UART interface.
2. Use your preferred development environment to load and run firmware.
3. Test the metal detector according to the provided schematic and design guidelines.
> Note: Always follow proper safety procedures when working with electronic circuits and during the assembly process.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
