# Adjustable Voltage Regulator Circuit with PCB Design

## Project Overview
This project involves designing an adjustable voltage regulator circuit using the **LM317T** IC, suitable for powering low-voltage devices like sensors or small electronics. The design includes a bridge rectifier, filtering capacitors, and a regulator to output a stable 3.7V DC. The PCB layout was designed using **Eagle CAD software**.

## Features
- Adjustable output voltage using LM317T.
- Efficient ripple reduction using capacitors.
- Outputs a stable 3.7V DC voltage.
- Designed for compact PCB layout.

## Components Used
- **LM317T**: Voltage regulator IC for adjustable output.
- **Bridge Rectifier**: Converts AC to DC.
- **Capacitors**: For filtering and smoothing ripples.
- **Resistors**: Sets the output voltage in the LM317 circuit.
- **Transformer**: Steps down the input AC voltage.
- **Miscellaneous**: Diodes, tactile switch, 5V buzzer, and a 3.7V battery.

## PCB Design
The PCB was designed using **Eagle CAD software**:
- Schematic captures the design and connections.
- Compact layout for easy implementation.
- Gerber files included for manufacturing.

### Schematic and PCB Images
- **Schematic**:
  ![Schematic](path/to/schematic-image.png)
- **PCB Layout**:
  ![PCB Layout](path/to/pcb-layout-image.png)

## How It Works
1. The transformer steps down AC voltage to a suitable level.
2. The bridge rectifier converts AC to pulsating DC.
3. Filter capacitors smooth the output voltage.
4. The LM317T regulator outputs a stable and adjustable voltage.
5. The output voltage is set to 3.7V using appropriate resistors.

## Files in Repository
- `Schematic.sch`: Eagle schematic file.
- `PCB.brd`: Eagle PCB layout file.
- `Gerber Files`: Ready for PCB manufacturing.
- `README.md`: Project documentation.

## Applications
- Powering low-voltage devices like sensors and microcontrollers.
- Educational purposes for learning about PCB design and voltage regulation.

## How to Use
1. Download the schematic and PCB files.
2. Open the files in **Eagle CAD** or any compatible software.
3. Review and modify the design if necessary.
4. Use the Gerber files to manufacture the PCB.
5. Assemble the components on the PCB and test the circuit.

## License
This project is open-source and available under the **MIT License**.

## Author
- **Abhinav Tripathi**

Feel free to contribute or suggest improvements!
