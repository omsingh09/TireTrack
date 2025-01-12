# Car Tire Pressure Monitoring System (TPMS)

## Overview

This project implements a **Car Tire Pressure Monitoring System (TPMS)** using C programming language and Raspberry Pi. The system continuously monitors the pressure of all four tires and triggers an alert (using an LED or buzzer) if the tire pressure drops below a predefined threshold. It also displays the tire pressure values on the console in real-time.

## Features

- **Real-Time Monitoring**: Monitors tire pressures of all four tires continuously.
- **Alerts**: Triggers an alert (LED/Buzzer) when tire pressure is below the predefined safe threshold.
- **Console Output**: Displays the tire pressure for each tire on the console every second.
- **Continuous Monitoring**: Continuously checks tire pressure every second and updates accordingly.

## Hardware Components

- **Pressure Sensors** for each tire.
- **Raspberry Pi** (or any compatible microcontroller like Arduino).
- **Buzzer or LED** for alert system.
- **WiringPi Library** for GPIO control on Raspberry Pi.
- **Breadboard and Wires** for connecting components.

## Installation and Setup

### 1. Install WiringPi

Before running the code, ensure that **WiringPi** is installed on your Raspberry Pi or compatible microcontroller.

To install WiringPi, run the following commands:

```bash
sudo apt-get update
sudo apt-get install wiringpi
