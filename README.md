# Home Automation System using IoT and Alexa

A smart home automation prototype that enables users to control and monitor household devices via smartphone and **Amazon Alexa** voice commands. Built using **NodeMCU**, **Arduino**, and various sensors and actuators to enhance home safety and control.

---

## 🏠 Overview
This system allows users to:
- Remotely control lights, fans, and door locks via Alexa or smartphone
- Monitor environmental factors like gas, flame, temperature, and light
- React to sensor inputs automatically for safety and convenience

---

## 🔌 Tech Stack
- **Hardware**: NodeMCU (ESP8266), Arduino Uno, Relay Module
- **Voice Control**: Amazon Alexa via Sinric Pro
- **Sensors Used**:
  - **DHT11** – Temperature and humidity sensor
  - **MQ2 Gas Sensor** – Gas/leakage detection
  - **Flame Sensor** – Fire detection
  - **LDR** – Light sensing for auto light control
- **Actuators**:
  - **DC Fan** – Auto-cooling based on DHT11
  - **Solenoid Lock** – Door lock/unlock control via Alexa
- **Software**: Arduino IDE, ESP8266WiFi, HTTP requests, Sinric Pro integration

---

## ⚙️ Key Features
- Control devices using Alexa or custom commands
- Receive feedback from sensors (e.g., gas alert triggers fan or notification)
- Automatic responses based on sensor thresholds
- Replaced Blynk with Alexa + Sinric Pro due to cost constraints

---

## 📐 Circuit Overview
- **NodeMCU** connects to sensors and actuators via GPIO pins
- Relay module controls AC appliances safely
- Solenoid lock powered via transistor for door automation
- Sensor readings processed in Arduino logic for real-time response

---

## 🧠 What I Learned
- Integrating multiple sensors with NodeMCU
- Writing logic for automatic and manual control
- Using Amazon Alexa with IoT devices via Sinric Pro
- Designing cost-effective, scalable smart systems

---

## 🚀 Future Enhancements
- Add mobile dashboard for manual control & data logs
- Add voice alerts and notifications via push API
- Expand to multi-room environment

---

## ✍️ Author
Pratham Govalkar — Final year IoT/Embedded mini project
