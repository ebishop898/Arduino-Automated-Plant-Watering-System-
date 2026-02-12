# Automated Plant Watering System (Arduino)

by *Emily Bishop*

An automated plant watering system built using **Arduino**, **soil moisture sensors**, and **water pumps** to monitor soil conditions and water plants as needed. The system responds to real-time moisture levels, ensuring plants receive adequate water without manual intervention.

This project was developed over a **two-week period** as a **final project for CSC 235: Physical Computing**, with a focus on integrating hardware, sensors, and control logic into a reliable physical system.

## 🌱 Features
- Real-time soil moisture monitoring
- Automatic activation of water pump when soil is dry
- Sensor-based decision making
- Reliable, hands-off plant watering
- Modular design for easy expansion (additional sensors or pumps)

## 🛠️ Built With
- **Arduino**
- **Soil moisture sensors**
- **Water pump**
- Breadboard, wiring, and basic electronic components
- Arduino IDE (C/C++)

## 🔌 Hardware Components
- Arduino microcontroller
- Soil moisture sensor(s)
- Water pump
- Power supply
- Tubing and wiring

## 🚀 How It Works
1. The soil moisture sensor continuously reads moisture levels from the soil.
2. The Arduino compares the sensor readings to a predefined threshold.
3. If the soil is too dry, the Arduino activates the water pump.
4. Once sufficient moisture is detected, the pump turns off.

## ▶️ Getting Started

### Prerequisites
- Arduino IDE installed  
  https://www.arduino.cc/en/software
- Arduino board and compatible hardware components

### Running the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/ebishop898/Arduino-Automated-Plant-Watering-System-
2. Open the .ino file in the Arduino IDE.
3. Connect your Arduino and hardware components.
4. Upload the code to the Arduino.
5. Monitor the system and adjust moisture thresholds as needed.
