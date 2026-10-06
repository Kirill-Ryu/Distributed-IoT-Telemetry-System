# 📡 Distributed IoT Telemetry System

> ** Notice Regarding Source Code**
> This project was developed as a Master of Engineering (MEng) assignment. To comply with the university's academic integrity and anti-plagiarism policies, **the source code is maintained in a private repository**.
> This README provides an overview of the project's architecture, technology stack, and key implementation details. (Source code access can be provided upon request during interviews or for review purposes).

## Project Overview
- **Period:** Mar 2026 - Apr 2026
- **Context:** MEng (Master of Engineering) Assignment
- **Goal:** To architect and deploy a robust distributed IoT telemetry pipeline for collecting real-time sensor data and automating actuator control.

## Tech Stack & Environment
- **Language:** C++
- **Protocol/Middleware:** MQTT, Mosquitto, JSON
- **Hardware:** Raspberry Pi, Hardware Inclination Sensor, Physical LEDs
- **Infrastructure:** VMware Workstation Pro (3 Separate Virtual Environments)

## Key Features & Implementation

### 1. Distributed IoT Telemetry Pipeline Architecture
- Architected a distributed system across **three separate VMware virtual environments** using C++.
- Successfully deployed a secure Mosquitto MQTT Broker, Publisher, and Subscriber applications on individual VMs, ensuring component isolation and system scalability.

### 2. Robust Sensor and Actuator Applications (Raspberry Pi)
- Developed highly reliable hardware control applications running on Raspberry Pi.
- Implemented **advanced MQTT features** to handle network instability and unexpected node disconnections gracefully:
  - **QoS (Quality of Service) Levels:** Ensured reliable message delivery across the pipeline.
  - **LWT (Last Will and Testament):** Configured automated system notifications for unexpected client disconnections.
  - **Retained Messages:** Enabled new subscribers to instantly synchronize with the latest system state upon connection.
  - **Persistent Connections:** Maintained continuous and stable communication sessions.

### 3. Embedded State Machine and Automated Control
- Processed and parsed real-time hardware inclination data into structured JSON payloads.
- Designed an **embedded state machine** that automatically controls physical LED actuators based on specific inclination thresholds and real-time sensor inputs.

## System Architecture & Demo



---
*If you have any questions about the technical details or would like to request access to the source code for review purposes, please feel free to contact me.*
* **Email:** boongwbg@gmail.com
* **LinkedIn:** www.linkedin.com/in/chunghyeon
