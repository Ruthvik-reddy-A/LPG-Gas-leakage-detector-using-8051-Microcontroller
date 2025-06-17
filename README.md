# 🔥 LPG Gas Leakage Detection Using 8051 Microcontroller

This project is a microcontroller-based LPG gas leakage detection system that senses harmful gas concentrations using the **MQ-6 sensor**, activates a **buzzer and exhaust fan**, and displays the status on an **LCD screen** using the **AT89S52 (8051)** microcontroller.

---

## 📌 Abstract

LPG gas leaks are hazardous, causing fire accidents and suffocation. This system detects gas leakage using the MQ-6 sensor and alerts users through:
- **Audible alarm (buzzer)**
- **Visual alert (LED)**
- **Automatic exhaust fan activation**

The entire system is implemented using **AT89S52** (8051 microcontroller) programmed in **Keil µVision3 IDE**.

---

## 🎯 Objectives

- Rapid and accurate LPG leak detection
- Alerting through buzzer and LED
- Exhaust fan activation for ventilation
- Real-time gas level display on LCD

---

## ⚙️ Working Principle

1. **Gas Detection**: The MQ-6 sensor detects LPG gas in the environment.
2. **Signal Processing**: Sensor output is fed to the 8051 microcontroller.
3. **Alarm Activation**: If the gas exceeds threshold level:
   - Buzzer and LED are activated
   - Exhaust fan is turned on
   - LCD displays "Environment Unsafe"
4. If gas is below the threshold, the system displays "Environment Safe".

---

## 🧱 Flow Chart


![image](https://github.com/user-attachments/assets/51fb0f6b-2d98-4a12-b536-a32751a3d481)


---

## 📐 Circuit Diagram


<img width="283" alt="image" src="https://github.com/Ruthvik-reddy-A/LPG-GAS-LEAKAGE-DETECTOR-USING-8051-Microcontroller/assets/73007037/7cd93bc0-2bf9-4bbe-ba0c-8dece193ff5b">





---
