# 🛗 Automated Elevator Overload Detection System

## 📌 Project Overview

This project presents an Arduino-based Automated Elevator Overload Detection System designed to improve passenger safety through real-time occupancy monitoring. The system uses Infrared (IR) sensors to detect passengers entering and exiting the elevator, continuously updating the occupancy count on an LCD display.

When the number of occupants exceeds the predefined capacity, the system activates an audible buzzer alert to notify passengers and operators about the overload condition. The proposed solution is cost-effective, modular, and can be easily integrated into existing elevator systems.

---

## 🎯 Objectives

- Develop an automated elevator occupancy monitoring system.
- Detect passenger entry and exit using IR sensors.
- Display real-time occupancy using an LCD display.
- Generate overload alerts using a buzzer.
- Improve elevator safety through automatic overload detection.
- Provide a low-cost and scalable monitoring solution.

---

## ⚙️ System Overview

The system consists of four major modules:

- Sensor Module
- Processing Module
- Display Module
- Alert Module

The monitoring process includes:

- Passenger Entry Detection
- Passenger Exit Detection
- Occupancy Counting
- Capacity Monitoring
- Overload Detection
- Audible Alert Generation

---

## 🛠️ Hardware Components

- Arduino Uno (ATmega328P)
- 2 × Infrared (IR) Sensors
- 16×2 LCD Display with I2C Module
- Active Buzzer
- Breadboard
- Jumper Wires
- USB Power Supply

---

## 💻 Software Requirements

- Arduino IDE
- Embedded C / Arduino Programming
- Wire Library
- LiquidCrystal_I2C Library

---

## 🔄 Working Principle

The system continuously monitors the state of two IR sensors positioned at the elevator entrance.

- Entry sensor increments the passenger count.
- Exit sensor decrements the passenger count.
- The LCD displays the current occupancy in real time.
- When occupancy exceeds the preset limit, the buzzer is activated.
- The alarm automatically turns off once occupancy returns to a safe level.

---

## ✨ Key Features

- Real-Time Occupancy Monitoring
- Automatic Passenger Counting
- Elevator Overload Detection
- Audible Warning System
- LCD-Based User Interface
- Arduino-Based Control System
- Low-Cost Hardware
- Easy Installation
- Modular Design

---

## 📊 System Specifications

| Component | Specification |
|-----------|---------------|
| Microcontroller | Arduino Uno (ATmega328P) |
| Display | 16×2 LCD with I2C |
| Sensors | 2 × IR Sensors |
| Alert Device | Active Buzzer |
| Operating Voltage | 5V DC |
| Programming | Arduino IDE |

---

## 🚀 Applications

- Residential Buildings
- Commercial Complexes
- Shopping Malls
- Hospitals
- Office Buildings
- Smart Buildings
- Public Infrastructure
- Occupancy Monitoring Systems

---

## 📈 Advantages

- Low Cost
- Easy to Implement
- Accurate Occupancy Counting
- Automatic Overload Detection
- Improved Passenger Safety
- Low Maintenance
- Scalable Design
- Energy Efficient

---

## 🔮 Future Scope

Future enhancements may include:

- Weight Sensor Integration
- IoT-Based Remote Monitoring
- GSM Alert System
- Mobile Application Support
- AI-Based Passenger Detection
- Camera-Based Occupancy Detection
- Cloud Data Logging
- Smart Building Integration

---

## 👨‍💻 Author

**Snehil Raj**

B.Tech – Electrical and Electronics Engineering

Vellore Institute of Technology (VIT), Vellore

---

## 📄 Project Report

This repository contains the complete Course Based Design Project (CBDP) on the Design and Implementation of an Automated Elevator Overload Detection System, including hardware implementation, software development, circuit design, algorithm, testing methodology, and performance evaluation.

---

## ⭐ Conclusion

This project demonstrates an efficient and affordable elevator overload detection system using Arduino and IR sensor technology. By continuously monitoring passenger occupancy and providing instant overload alerts, the system enhances elevator safety while reducing implementation cost. Its modular architecture and simple hardware design make it suitable for educational projects, research, and practical smart building applications.

---

## 📜 License

This repository is intended for **educational, academic, and research purposes only**.
