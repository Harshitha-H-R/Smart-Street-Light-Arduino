# Smart Street Light System using Arduino UNO

## Overview
This project implements an automatic smart street lighting system that operates based on ambient light conditions and vehicle detection.  
It aims to reduce power consumption by controlling light intensity intelligently.

## Components Used
- Arduino UNO  
- IR Sensors (3)  
- LDR Sensor  
- LEDs  
- Resistors  

## Working Principle
- LDR detects day or night conditions.
- During daytime, street lights remain OFF.
- At night, lights remain DIM by default.
- When a vehicle is detected using IR sensors, only the nearby street light glows BRIGHT.

##  Control Logic
- Sensor values are continuously monitored.
- Conditional logic adjusts LED brightness using PWM.
- Energy efficiency is achieved by selective illumination.

## 🔌 Circuit Diagram
![circuit Diagram](circuit/circuit_diagram.jpeg)

##  Programming Language
- C++ (Arduino)

## Learning Outcomes
- Sensor interfacing  
- Conditional decision making  
- PWM-based brightness control  
- Embedded system fundamentals  

##  Future Enhancements
- IoT-based monitoring
- Motion sensors
- Solar-powered street lights

---
Developed by **Harshitha H R**  
B.Tech – Electrical & Electronics Engineering
