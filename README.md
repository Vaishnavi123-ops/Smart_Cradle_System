# Smart_Cradle_System
This project presents a Smart Cradle System that utilizes a microcontroller and various sensors to ensure infant safety and automate cradle functions. The system combines sound sensing, wetness detection, limit switches, and DC motor control to swing the cradle and alert caregivers when needed.

## 📷 Project Overview

This Smart Cradle System leverages an AT89C52 microcontroller and various sensors to automate cradle motion and ensure infant comfort and safety. When the baby cries or wets the diaper, the system responds with alerts and motorized cradle movement.

---

## 🔧 Features

- 🔊 **Cry Detection** via sound sensor
- 💧 **Wetness Detection** using a moisture sensor
- 🔁 **Automated Cradle Swinging** through DC motor
- 🔔 **Buzzer Alerts** for parents/caregivers
- 🛑 **Limit Switches** and **Hall Effect Sensor** for motion control
- ⚡ **Regulated Power Supply** using 7805 IC

---

## 🧩 Components Used

| Component                  | Description                                      |
|---------------------------|--------------------------------------------------|
| AT89C52 Microcontroller   | Core logic control unit (8051 family)            |
| Sound Sensor Circuit      | Detects crying using a transistor-based circuit  |
| Wet Sensor                | Detects diaper wetness through conductivity      |
| Hall Effect Sensor (3144) | Monitors cradle's position                       |
| L293D Motor Driver        | Controls DC motor for swinging cradle            |
| DC Motor                  | Mechanism to swing the cradle                    |
| Buzzer                    | Audible alert system                             |
| Limit Switches            | Prevents over-swinging of the cradle             |
| Power Supply (7805 IC)    | Converts 230V AC to 5V DC                        |
| Crystal Oscillator        | Provides timing to microcontroller               |

---

## ⚙️ Circuit Functionality

1. **Sound Sensing**: Detects baby's cry and triggers the microcontroller.
2. **Wet Sensor**: Activates when moisture is present, indicating a wet diaper.
3. **Swing Motor Control**: L293D receives commands from the microcontroller to swing the cradle.
4. **Alert Mechanism**: Buzzer is activated for any distress signals.
5. **Limit Switches & Hall Sensor**: Ensures cradle doesn't exceed safe swing range.

---

## 🔌 Power Supply

- **Input**: 230V AC
- **Output**: Regulated +5V DC (via 7805)
- Smoothened with capacitors and diode bridge.

---

## 🖥️ Programming Environment

- **Language**: Embedded C
- **IDE**: Keil µVision
- **Programmer**: Flash Magic (for AT89C52)

---

## 🧠 Future Enhancements

- Integrate Wi-Fi/Bluetooth (ESP8266) for mobile notifications
- Add mobile app support for monitoring
- Camera module for remote video feed
- Battery backup system for power failure cases

---

## 📁 Repository Structure

