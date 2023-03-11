# Project-01: Basic LED Circuit - PCB

This project contains a KiCad 7.0.0 PCB design for a basic LED circuit. The PCB contains three footprints: `Connector_PinHeader_2.54mm` for the battery, `LED_THT:LED_D5.0 mm` for the LED, and `Resistor_THT:R_Axial_DIN0309_L9.0mm_D3.2mm_P15.24mm_Horizontal` for the 470 ohms resistor.

## Table of Contents
- Circuit Diagram
- Components
- PCB Design
- Usage
- License

## Circuit Diagram

![LED Circuit Diagram](C:\Users\nx018023\Desktop\GitHub\PCB-Designing-with-KiCad\Basic LED Circuit_PCB\Image_Files\Basic LED Circuit Diagram.jpg) 

The circuit diagram above shows the basic LED circuit. The LED is connected in series with a resistor and a power source. The resistor limits the current flow through the LED and prevents it from burning out. The circuit is designed for a 9V power supply and uses a 470 Ohm resistor.

## Components

The components used in the circuit are:

- LED (light-emitting diode)
- Resistor (470 Ohm)
- Power source (9V battery)

## PCB Design

The KiCad PCB design for the basic LED circuit is shown below:

![LED Circuit PCB Design](C:\Users\nx018023\Desktop\GitHub\PCB-Designing-with-KiCad\Basic LED Circuit_PCB\Image_Files\Basic LED Circuit_PCB.jpg)  

The PCB contains three footprints: Connector_PinHeader_2.54mm for the battery, LED_THT:LED_D5.0 mm for the LED, and Resistor_THT:R_Axial_DIN0309_L9.0mm_D3.2mm_P15.24mm_Horizontal for the 470 ohms resistor. The design follows the circuit diagram shown earlier, with the battery connected to the vertical pin header, the resistor connected to the horizontal resistor footprint, and the LED connected to the LED footprint.

## Usage

To use the PCB, follow these steps:

1. Gather the components: LED, resistor, battery, and PCB.
2. Solder the LED to the LED footprint on the PCB.
3. Solder the resistor to the resistor footprint on the PCB.
4. Connect the anode (positive lead) of the LED to one end of the resistor.
5. Connect the other end of the resistor to the positive terminal of the battery.
6. Connect the cathode (negative lead) of the LED to the negative terminal of the battery.
7. Insert the battery into the vertical pin header on the PCB.
   
Once the circuit is connected, turn on the power source to light up the LED.

## Contributing

Contributions to this repository are welcome! If you want to contribute a new PCB design, create a new folder with the project name and add the necessary files. Ensure that the files are compatible with the latest version of KiCad software.

Before submitting a pull request, make sure to test the design and generate the Gerber files to ensure that everything is working properly.

## License

This repository is licensed under the [Unlicense](https://unlicense.org). You are free to use and modify the designs in this repository for personal or commercial purposes. However, we do not guarantee the accuracy or reliability of the designs, and we are not responsible for any damages or liabilities that may result from their use.
