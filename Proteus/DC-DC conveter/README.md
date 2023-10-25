# DC-DC Converter

**Table of Contents**
- [Description](#description)
- [Features](#features)
- [Components](#components)
- [Schematic](#schematic)
- [3D Model](#3d-model)
- [Usage](#usage)
- [License](#license)

## Description

This project presents a simple yet effective circuit for powering a 1W LED using your car's battery. It utilizes the MC34063 IC as a buck converter, a versatile monolithic switching regulator sub-system designed for DC-DC conversion.

The MC34063 device integrates multiple functions into an 8-pin dual in-line package, including an internal temperature-compensated reference, a comparator, a controlled duty-cycle oscillator with an active current-limit circuit, a driver, and a high-current output switch. These features make it an ideal choice for efficient voltage conversion.
## Features

- Efficiently powers a 1W LED from a car battery.
- Utilizes the MC34063 IC as a buck converter.
- Internal temperature-compensated reference for stability.
- Controlled duty-cycle oscillator with current-limit protection.
- Compact and versatile design.

## Components

- MC34063 IC
- Passive components (resistors, capacitors)
- 1W LED
- Car battery
## Schematic

![Schematic](/DC-DC conveter.png)

## Simulation

![PCB Layout](/img/Sketch.png)



## Usage

To use this circuit to power a 1W LED from your car battery, follow these steps:

1. **Components**: Gather the necessary components, including the MC34063 IC, passive components, a 1W LED, and your car battery.

2. **Assembly**: Assemble the circuit according to the provided schematic. Ensure correct component connections.

3. **Power On**: Connect the circuit to your car battery and observe the LED's illumination. The buck converter will efficiently regulate the voltage to power the LED.

4. **Adjustment (Optional)**: Depending on your specific requirements, you may need to fine-tune the circuit. Refer to the datasheet for the MC34063 IC for more information.

## Authors

- [@Shubham Singh](https://github.com/Shubham722-227)
- [@Jitendra Sharma](https://github.com/jitendrasharma04)

## License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

