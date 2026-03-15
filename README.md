# Secure Smart Home Automation System

An **IoT-based intelligent smart home system** designed to enhance **security, safety, and energy efficiency** using multiple sensors, cloud connectivity, and AI-powered access control.

This project integrates **face recognition entry, gas leakage detection, automated climate control, intelligent lighting, container level monitoring, emergency alerts, and wearable health monitoring** into a unified smart home platform. 

# Features

### Face Recognition Door Access

* Uses **computer vision with OpenCV** for biometric authentication
* Automatically unlocks doors for authorized users
* Logs unknown access attempts and sends alerts

### Gas Leak Detection

* **MQ-5 gas sensor** detects hazardous gas levels
* Triggers alarm and sends immediate notifications

### SOS Emergency Alert

* Dedicated **emergency button**
* Sends instant alerts to predefined contacts

### Smart Climate Control

* **Temperature sensors** automatically control fans and air conditioning
* Maintains comfortable indoor conditions

### Intelligent Lighting System

* Uses **PIR motion sensor + LDR**
* Automatically turns lights on/off based on occupancy and ambient light

### Kitchen Storage Monitoring

* Monitors container levels using **ultrasonic/weight sensors**
* Sends notifications when supplies are low

### Wearable Health Monitoring

* ESP32 wearable device measures:

  * Heart rate
  * Movement patterns
  * Sleep behavior
* Can trigger alerts on abnormal readings

### Cloud Dashboard

* Real-time monitoring of:

  * Sensors
  * Home devices
  * Health metrics
* Secure remote control through web/mobile interface

# System Architecture

The system uses a **modular IoT architecture** where a central microcontroller communicates with sensors, actuators, wearable devices, and cloud services. 

**Core Components**

* NodeMCU / ESP8266 (Central Controller)
* Raspberry Pi (Face Recognition Processing)
* IoT Sensors
* Cloud IoT Platform
* Mobile/Web Dashboard

Sensors → Microcontroller → Cloud → User Dashboard
                ↓
           Actuators

# Hardware Components

| Component         | Purpose                            |
| ----------------- | ---------------------------------- |
| Raspberry Pi      | Face detection and processing      |
| NodeMCU / ESP8266 | IoT controller                     |
| MQ-5 Gas Sensor   | Gas leakage detection              |
| DHT11/DHT22       | Temperature & humidity             |
| PIR Sensor        | Motion detection                   |
| LDR Sensor        | Ambient light detection            |
| Ultrasonic Sensor | Container level monitoring         |
| ESP32 Wearable    | Heart rate and activity monitoring |
| Relay Modules     | Control appliances                 |
| Servo Lock        | Smart door lock                    |


# Software & Technologies

**Programming**

* Python
* Arduino C/C++

**Libraries**

* OpenCV
* ESP8266 WiFi
* MQTT

**Technologies**

* Internet of Things (IoT)
* Computer Vision
* Cloud Computing
* Embedded Systems
* Sensor Networks


# Security Features

* **TLS encrypted communication**
* **Biometric authentication**
* **Multi-channel alerts (WiFi + GSM fallback)**
* **Device authentication**
* **Access logging and monitoring** 

# Results

The system demonstrated:

* **~95% face recognition accuracy**
* **Gas leak alerts within 1–2 seconds**
* **Door unlock response within 2–3 seconds**
* **~25% reduction in unnecessary energy consumption** through automated lighting and fan control. 

# Future Improvements

* Machine learning based **predictive automation**
* **Advanced anomaly detection**
* **Voice assistant integration**
* **Telemedicine integration**
* Wearable upgrades with **SpO₂ and ECG monitoring** 

# Repository Structure

smart-home-automation/
│
├── hardware/
│   ├── circuit-diagrams
│   ├── sensor-modules
│
├── firmware/
│   ├── nodemcu-code
│   ├── esp32-wearable
│
├── computer-vision/
│   ├── face-recognition
│   ├── training-model
│
├── dashboard/
│   ├── web-interface
│
├── docs/
│   ├── research-paper
│
└── README.md


# Applications

* Smart homes
* Assisted living for elderly
* Energy-efficient buildings
* Remote home monitoring
* Health-aware residential environments

# Author

**Suyash Mangla**
Computer Science
Birla Institute of Technology and Science, Pilani
Email: f20230593@pilani.bits-pilani.ac.in



