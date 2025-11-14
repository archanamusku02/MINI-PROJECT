

# 🛡️ IoT-Based Surveillance Robot

An autonomous, multi-purpose surveillance and rescue robot powered by IoT and Arduino. Designed to operate in hazardous environments, this robot enables remote monitoring, real-time data transmission, and intelligent decision-making through sensor integration and cloud connectivity.


## 📌 Project Overview

This project combines robotics and IoT to build a surveillance robot capable of:

- Remote monitoring via Wi-Fi camera
- Autonomous navigation and obstacle avoidance
- Real-time data transmission to cloud platforms
- Night vision and long-range surveillance
- Object detection and recognition

## 🧠 Key Technologies

- **Arduino UNO** (ATmega328 microcontroller)
- **ESP32 Camera Module** for video streaming
- **Wi-Fi Module** for IoT connectivity
- **DC Motors & L293D Motor Driver** for mobility
- **16x2 LCD Display** for status output
- **Cloud Platform** for data storage and remote access
- **MQTT / HTTP / WebSocket** protocols for communication


## ⚙️ Features

- 📷 Real-time video surveillance with night vision
- 🌐 IoT-enabled remote control via smartphone or PC
- 🔄 Bidirectional data transmission
- 🧭 Autonomous navigation with obstacle detection
- 🔐 Secure data communication with encryption
- 🔋 Power-efficient design with sleep modes


## 🏗️ System Architecture

The robot is divided into two main sections:

1. **Mobility Section**: Includes motors, wheels, sensors, and Arduino control.
2. **User Control Section**: Enables remote access via IoT and cloud services.

### Prerequisites

- Arduino IDE
- ESP32 Camera libraries
- MQTT/HTTP client setup
- Cloud platform (e.g., Firebase, AWS IoT)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/iot-surveillance-robot.git
   ```
2. Open the Arduino IDE and upload the code to Arduino UNO.
3. Connect the ESP32 Camera and configure Wi-Fi credentials.
4. Set up cloud platform for data logging and remote access.

## 🧪 Testing & Optimization

- Simulate various environments for mobility and connectivity
- Optimize latency and bandwidth usage
- Test cloud integration and data security




