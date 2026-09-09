# Fuel Cell Monitoring System – 6-Layer PCB

## Overview

A custom **6-layer mixed-signal PCB** designed in **KiCad** for monitoring a **500 W PEM fuel cell system**.

The board measures fuel-cell voltage and current, conditions the analog signals, performs ADC conversion, provides digital isolation, and interfaces with an **ESP32-S3**.

## Main Features

- Fuel-cell voltage measurement
- Fuel-cell current measurement up to 20 A
- Analog signal conditioning and filtering
- Precision voltage references
- High-resolution ADC measurement
- Digital isolation
- ESP32-S3 interface

## Main Components

| Component | Function |
|---|---|
| ESP32-S3 | Microcontroller |
| ADS8329 | ADC |
| MAX49925 | Current measurement |
| MAX6070 | Precision voltage reference |
| AD8031 / AD8032 | Analog signal conditioning |
| ADA4099 | Precision analog amplifier |

## PCB Design

The PCB is designed as a **6-layer mixed-signal board** using KiCad.

The multilayer design supports:

- Analog and digital signal separation
- Stable power and ground distribution
- Sensitive ADC signal routing
- High-current routing
- Improved signal integrity and noise performance

## Project Structure

```text
Fuel-Cell-Monitoring-PCB/
├── Docs/
│   ├── Fuel Cell Monitoring Report.pdf
│   └── Images/
├── Kicad/
│   ├── *.kicad_pro
│   ├── *.kicad_sch
│   ├── *.kicad_pcb
│   ├── My Symbols/
│   └── MY Footprints/
├── README.md
└── .gitignore
```

## Tools

- **KiCad** – Schematic and PCB design
- **ESP32-S3** – Digital control and interface
- **GitHub** – Project version control and documentation

## Future Work

- PCB manufacturing and assembly
- Hardware bring-up and testing
- Sensor calibration
- Measurement accuracy evaluation
- ESP32-S3 firmware development
- Real-time monitoring and data logging

## License

This project is intended for educational, engineering, and portfolio purposes.
