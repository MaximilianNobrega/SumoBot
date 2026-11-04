# SumoBot Remote Controller
**PCB Layout Design | Hardware Assembly | Electrical Testing**

## Project Overview

This project involved the development of a custom printed circuit board (PCB) for a SumoBot remote controller. The controller uses a Raspberry Pi Pico microcontroller, an Adafruit Gamepad QT, and infrared (IR) transmission circuitry.

Working from a provided circuit schematic, I independently designed the complete two-layer PCB layout using Altium Designer. I then prepared the design for manufacturing, coordinated PCB fabrication through JLCPCB, and personally soldered and assembled the finished hardware.

The completed PCB was successfully assembled and tested.

## My Contributions

### PCB Layout Design
- Independently designed the complete two-layer PCB layout in Altium Designer using a provided schematic.
- Performed component placement and trace routing for the microcontroller, gamepad interface, power circuitry, and IR transmitter.
- Implemented ground copper pours.
- Ran multiple design rule checks (DRCs), identifying and resolving clearance violations.
- Verified manufacturing compatibility using JLCPCB's design checks.

### Manufacturing and Assembly
- Generated Gerber and drill files for PCB fabrication.
- Coordinated manufacturing through JLCPCB.
- Personally soldered and assembled the PCB components.
- Verified successful operation of the completed hardware.

### Hardware Testing
- Tested voltage regulation and power circuitry using laboratory equipment.
- Verified infrared transmitter and receiver functionality.
- Demonstrated infrared reception at distances up to 8.23 meters.

## Hardware Components

| Component | Function |
|---|---|
| Raspberry Pi Pico | Main microcontroller |
| Adafruit Gamepad QT | User input interface |
| TSAL6400 IR LED | Infrared transmission |
| Transistor driver circuitry | IR LED switching |
| Voltage regulation circuitry | Power conditioning |

## Software and Equipment

**PCB Design:** Altium Designer

**Manufacturing:** JLCPCB

**Testing Equipment:** Oscilloscope, digital multimeter, benchtop DC power supply

## PCB Design

The PCB was designed with two copper layers and ground pours. The layout was iteratively refined to resolve design-rule violations and satisfy manufacturing requirements.

### PCB Layout Screenshots

*Top-layer and bottom-layer Altium screenshots will be added here.*

## Manufacturing

The completed PCB design was submitted to JLCPCB for fabrication using the generated Gerber and drill files.

The manufacturing files are included in this repository for reference.

## Completed Hardware

*Photographs of the manufactured PCB and assembled controller will be added here.*

## Results

- Successfully completed and manufactured the custom two-layer PCB.
- Resolved PCB clearance violations through iterative design-rule verification.
- Soldered and assembled the physical controller hardware.
- Verified successful operation of the assembled PCB.
- Demonstrated infrared reception at distances up to 8.23 meters.

## Project Attribution

The original circuit schematic was provided as part of the project. My individual contributions included PCB layout design, design-rule verification, manufacturing preparation, soldering, assembly, and hardware testing.
