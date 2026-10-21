## Water Quality Monitoring System

## Overview

An ESP32-based embedded system for monitoring water quality using sensors that measure pH, water temperature and electrical conductivity. The system displays measurements locally and transmits data for remote monitoring.

## Hardware

- ESP32 microcontroller
- PH-4502C pH sensor
- Submersible water-temperature sensor
- Electrical conductivity sensor
- OLED display

## Software and Technologies

- **C++ :** Firmware development and sensor interfacing.
- **FreeRTOS:** Real-time task scheduling and concurrent monitoring.
- **MQTT:** Communication of measurement data to a remote platform.
- **I2C:** Communication with the OLED display.

## Key Features

- Real-time water-quality measurements.
- Local display of sensor readings.
- Remote monitoring through MQTT.
- Modular design for future sensor integration.

## Future Improvements

- Cloud-based data visualisation and alerts.
- Data logging and historical analysis.
- Integration of sensors for detecting specific water contaminants.

## Note

The system provides water-quality indicators but does not independently confirm the presence or concentration of specific contaminants or establish whether water is safe to drink.
