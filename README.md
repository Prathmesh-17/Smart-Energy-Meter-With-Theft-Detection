## Overview

Smart Energy Meter with Theft Detection is an IoT-based system designed to monitor real-time electricity consumption and detect unauthorized power usage. The system uses ESP32 microcontrollers along with current and voltage sensors to compare supplied and consumed power, enabling accurate detection of electricity theft such as illegal tapping, meter bypassing, and unauthorized load connections.

## Features

* Real-time monitoring of voltage, current, and power consumption
* Electricity theft detection through supply-load comparison
* Detection of meter bypassing and illegal tapping
* Local processing using ESP32 for faster response
* IoT-enabled remote monitoring via Wi-Fi
* LCD display for live system status and measurements
* Alert generation for abnormal power usage
* Cost-effective and scalable design

## Problem Statement

Electricity theft and inaccurate energy monitoring result in significant financial losses for power distribution companies. Traditional energy meters lack real-time monitoring and theft detection capabilities. This project addresses these issues by continuously monitoring electrical parameters and automatically identifying suspicious power consumption patterns.

## System Architecture

The system consists of:

* 2 × ESP32 Microcontrollers
* AC Current Sensors
* AC Voltage Sensors
* 16x2 LCD Display
* LED Indicators
* Wi-Fi Communication Module (Built into ESP32)

One ESP32 monitors the power supplied from the source, while the second ESP32 monitors the power consumed by the load. The system continuously compares both measurements to identify abnormal differences that may indicate electricity theft.

## Block Diagram

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/3c3c1dd3-05d2-4026-b38e-cc4cd79ca599" />

## Working Principle

1. Current and voltage sensors collect electrical parameters.
2. ESP32 controllers process the sensor data in real time.
3. Supplied power and consumed power are continuously compared.
4. If the difference exceeds a predefined threshold, theft is detected.
5. Alerts are generated and displayed on the LCD.
6. Data can be transmitted wirelessly for remote monitoring and analysis.

## Hardware Components

| Component               | Quantity |
| ----------------------- | -------- |
| ESP32 Development Board | 2        |
| AC Current Sensor       | 2        |
| AC Voltage Sensor       | 2        |
| LCD 16x2 Display        | 1        |
| LED Indicators          | Multiple |
| Power Supply            | 1        |

## Hardware Implementation

<img width="559" height="360" alt="image" src="https://github.com/user-attachments/assets/694714bf-77e5-40dc-aa6c-2be5d0bd07ad" />

## IoT Webpage

<img width="646" height="345" alt="image" src="https://github.com/user-attachments/assets/a208cbae-c74f-404a-9eb6-7ac1b7b2c9e4" />

## Technologies Used

* ESP32
* Embedded C / Arduino IDE
* IoT
* Wi-Fi Communication
* Current & Voltage Sensing
* Energy Monitoring
* Theft Detection Algorithms

## Applications

* Residential Energy Monitoring
* Commercial Buildings
* Industrial Energy Management
* Smart Grid Systems
* Utility Power Distribution Networks

## Key Benefits

* Reduces electricity theft and revenue loss
* Improves billing transparency
* Minimizes manual inspection efforts
* Enhances power distribution efficiency
* Supports future smart city and smart grid applications
