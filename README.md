# Fuel Cell Monitoring System – 6-Layer PCB

## Overview

A custom **6-layer mixed-signal PCB** designed in **KiCad** for monitoring a **PEM fuel cell system**.

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

## Design Tools

- KiCad – Schematic capture and PCB layout
- ESP32-S3 – Microcontroller interface
- Multilayer PCB design for mixed-signal applications

## Project Structure

- `Kicad/` – KiCad schematics, PCB layout, symbols and footprints
- `Docs/` – Project report and documentation images
- `.gitignore` – Files excluded from Git tracking

## Project Status

PCB schematic and 6-layer PCB layout completed in KiCad.

## Future Improvements

- PCB manufacturing and assembly
- Hardware testing and calibration
- ESP32-S3 firmware development
- Measurement accuracy and noise evaluation
