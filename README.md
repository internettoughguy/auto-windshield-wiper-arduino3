# 🚗 Automatic Windshield Wiper System (Arduino-Based)

## 📌 Overview
This project presents the design and implementation of an **Automatic Windshield Wiper System** using Arduino and a rain sensor.

The system automatically detects rain intensity and activates windshield wipers without manual driver intervention. It demonstrates embedded systems design, sensor integration, and microcontroller-based control logic.

This project was developed as part of the Electric Circuit course.

---

## 🎯 Problem Statement

In traditional vehicles, windshield wipers are operated manually by the driver. This requires continuous monitoring of weather conditions and manual adjustment of the wiper speed.

During sudden rainfall, delayed reaction can:
- Reduce driver visibility
- Increase accident risk
- Cause unnecessary distraction

This project solves that problem by implementing an automated rain detection and wiper activation system.

---

## 🛠 Hardware Components

- Arduino Uno
- Rain Sensor Module
- 2 × SG90 Servo Motors
- Breadboard
- Jumper Wires

---

## ⚙️ Working Principle

1. The rain sensor detects water droplets on its surface.
2. The sensor outputs an analog voltage proportional to water intensity.
3. The Arduino reads the analog signal.
4. If the sensor value exceeds a defined threshold, the wipers activate.
5. If no rain is detected, the wipers stop automatically.

---

## 🧠 Control Logic

Let:

Vs = Sensor voltage  
Vth = Threshold voltage  

If:

Vs > Vth  

→ Wiper Motor = ON  

Else  

→ Wiper Motor = OFF  

This simple threshold-based logic allows real-time automated response to rainfall.

---

## 🔌 System Architecture

- Rain sensor connected to Arduino analog input (A0)
- Servo motors connected to digital PWM pins
- 5V power supplied directly from Arduino

---
