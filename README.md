# Rescue & Surveillance Drone for Women Safety

A real-time women safety system integrating an **SOS Smartwatch** with an **Autonomous Surveillance Drone** to provide immediate alerts, live GPS tracking, and real-time video evidence during emergencies.

---

## Project Overview

This project focuses on enhancing women’s safety using:

* A **wearable smartwatch** that sends Minor/Major alerts.
* A **drone** that automatically receives GPS coordinates and takes off for surveillance.
* A **control room interface** that receives and monitors alerts.

The system supports emergency response, live tracking, and surveillance during crisis situations.

---

## Objectives

* Provide quick emergency alerting during distress situations.
* Enable live location tracking using GPS.
* Deploy an autonomous drone to capture real-time video.
* Notify authorities instantly using GSM-based communication.

---

## System Architecture

### **1. Smartwatch Unit**

* Arduino Nano
* GPS Module (NEO-6M/7M)
* SIM800L GSM Module
* OLED Display (0.96")
* Push Buttons – Minor & Major Alert
* 3.7V Li-ion Battery

### **2. Drone Unit**

* APM 2.8 Flight Controller
* F450 Drone Frame
* A2212 1000KV BLDC Motors
* 30A ESCs
* 1045 Propellers
* FPV Camera + 5.8GHz Video Transmitter
* 3DR Telemetry Module (433MHz)
* LiPo 11.1V Battery

---

## Hardware List

| Component         | Description              |
| ----------------- | ------------------------ |
| Arduino Nano      | Smartwatch controller    |
| SIM800L           | Sends alert SMS messages |
| GPS NEO-6M        | Location tracking        |
| OLED Display      | Shows mode status        |
| Dual Push Buttons | Alert triggers           |
| APM 2.8           | Drone flight controller  |
| BLDC Motor 1000KV | Propulsion               |
| ESC 30A           | Motor control            |
| FPV Camera        | Live video feed          |
| 5.8GHz VTX        | Video transmission       |
| 3DR Telemetry     | Control room link        |
| LiPo Battery      | Power supply             |

---

## Software Used

* Arduino IDE
* Mission Planner
* T6 Config Software
* GoFPV Mobile App

---

## System Working

### **Mode 1 – Minor Alert**

1. User presses Minor Alert button.
2. GPS coordinates collected and sent via GSM.
3. Control room receives alert.
4. Drone dispatched to capture surveillance footage.

### **Mode 2 – Major Alert**

1. User presses Emergency Alert button.
2. Location + distress signal sent instantly.
3. Drone deployed + Police alerted.
4. Live video streamed through FPV.
5. Evidence recorded for investigation.

---

## Results & Outcomes

* Smartwatch successfully built and tested.
* Drone flight stability achieved.
* GPS tracking accurate within ~5m.
* FPV camera provided clear real-time footage.
* GSM module delivered alerts instantly.

---

## Future Scope

* AI-based violence detection on drone feed.
* Obstacle avoidance using LiDAR/Ultrasonic sensors.
* Facial recognition for identifying suspects.
* Multi-drone collaboration system.
* Dedicated Android App for monitoring.

---

## Contributors

* Prasudhi A
* Sonal Sajith M
* **Sourav Ratheesh K V**
* Vyshna P

---

## License

This project is licensed under the **MIT License**.

