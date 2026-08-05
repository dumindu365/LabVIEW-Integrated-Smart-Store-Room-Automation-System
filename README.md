# LabVIEW Integrated Smart Store Room Automation System
# Smart Store Room Automation System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![LabVIEW](https://img.shields.io/badge/LabVIEW-2020-blue.svg)](https://www.ni.com/en-us/shop/labview.html)
[![Arduino](https://img.shields.io/badge/Arduino-1.8.13-green.svg)](https://www.arduino.cc/)

## 🚀 Project Overview

A comprehensive LabVIEW-integrated smart room automation system that monitors environmental conditions and controls access through an intelligent door mechanism. This project demonstrates advanced integration of sensors, actuators, and IoT capabilities.

### 🌟 Key Features

- **Smart Access Door**: Automated sliding door with infrared presence detection
- **Air Quality Monitoring**: Real-time PM2.5 detection with active dust mitigation
- **Custom IR Distance Sensor**: Hand-made proximity sensor with 40cm range
- **Climate Dashboard**: Visual LED feedback for temperature and humidity
- **Energy Conservation**: Motion-based power management with delay timers
- **IoT Dashboard**: Real-time data visualization and remote monitoring

## 🏗️ System Architecture

### Hardware Components

| Component | Quantity | Purpose |
|-----------|----------|---------|
| 28BYJ-48 Stepper Motor | 1 | Automated door control |
| ULN2003 Driver | 1 | Motor driver |
| Sharp GP2Y1010AU0F | 1 | Dust particle detection |
| DHT22 Sensor | 1 | Temperature & Humidity |
| HC-SR501 PIR Sensor | 1 | Motion detection |
| IR LEDs & Photodiode | Set | Custom distance sensor |

### Software Stack

- **LabVIEW**: Main control logic and DAQ interface
- **Arduino**: Motor control and sensor data processing
- **Python**: IoT connectivity and Firebase integration
- **Web Dashboard**: Real-time monitoring interface

## 📋 Prerequisites

### Software Requirements
- LabVIEW 2020 or later
- NI-DAQmx driver
- Arduino IDE 1.8.13+
- Python 3.7+
- Firebase account (for IoT features)

### Hardware Requirements
- DAQ module (compatible with LabVIEW)
- Arduino Uno or compatible
- 5V DC power supply
- USB cables and breadboard



