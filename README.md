# 🚗 Vehicle Emergency Car Assist System

## 📌 Introduction
The Vehicle Emergency Car Assist System is an Arduino-based automated vehicle safety and driver-assistance project. It is designed to prevent accidents caused by driver drowsiness or loss of control by automatically taking corrective actions during emergency situations.

The system uses an eye blink sensor to monitor the driver’s eye condition and an ultrasonic sensor to detect the vehicle’s position relative to the road. When an emergency is detected, the system safely moves the vehicle to the roadside, stops it, and sends an alert message to a registered mobile number.

---

## ⚙️ Features
- Driver drowsiness detection using eye blink sensor
- Automatic left-side indicator activation
- Sensor-based steering toward roadside
- Automatic motor stop using relay
- Emergency SMS alert to registered phone number
- Real-time safety monitoring and control
- Automatic system reset for safety

---

## 🧠 Working Overview
- The system continuously monitors the driver’s eye status.
- If eyes are open, the vehicle operates normally.
- If eyes are not open:
  - Left indicator turns ON
  - Vehicle steers toward the left using servo motor
  - Ultrasonic sensor ensures safe roadside movement
  - Motor is stopped after reaching roadside
  - Emergency message is sent to a registered phone number
- The system resets to a safe state after emergency handling.

---

## 🔧 Hardware Components
- Arduino Uno / Nano  
- Eye Blink Sensor  
- Ultrasonic Sensor (HC-SR04)  
- Servo Motor (Steering Control)  
- Relay Module (Motor Control)  
- GSM Module (SIM800 / SIM900)  
- LEDs (Indicators)  
- Buzzer  
- Power Supply  
- Jumper Wires  

---

## 🛠 Applications
- Driver drowsiness detection systems
- Emergency vehicle assist systems
- Autonomous and semi-autonomous vehicles
- Smart transportation systems
- Industrial and campus transport vehicles

---

## 👨‍💻 Author
**Mohammad Zakariya**  
B.Tech – Electronics & Communication Engineering  
Embedded Systems | Arduino | Vehicle Automation

---
