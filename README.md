# 🔐 Fingerprint Door Unlock System Using Arduino

> A biometric-based smart door security system using an Arduino Uno and a fingerprint sensor. The system grants access only to authorized users by verifying their fingerprints.

---

## 📖 Overview

The **Fingerprint Door Unlock System** is an embedded systems project that replaces traditional keys with biometric authentication. When a registered fingerprint is detected, the Arduino unlocks the door using a servo motor or relay-controlled solenoid lock. Unauthorized users are denied access, and an alert is generated using a buzzer and LED indicators.

---

## ✨ Features

- 🔑 Fingerprint-based authentication
- 👤 Supports multiple enrolled fingerprints
- 🚪 Automatic door unlock and lock
- 🟢 Green LED for successful authentication
- 🔴 Red LED for unauthorized access
- 🔔 Buzzer notification
- ⚡ Fast response time
- 🛡️ Enhanced security

---

## 🛠️ Hardware Components

| Component | Quantity |
|-----------|:--------:|
| 🟦 Arduino Uno | 1 |
| 👆 R307 / AS608 Fingerprint Sensor | 1 |
| ⚙️ SG90 Servo Motor / 🔒 Solenoid Lock | 1 |
| 🔌 Relay Module | 1 |
| 💡 Green LED | 1 |
| ❤️ Red LED | 1 |
| 🔔 Buzzer | 1 |
| 📺 16×2 LCD (Optional) | 1 |
| 🔗 Jumper Wires | As Required |
| ⚡ 5V Power Supply | 1 |

---

## 💻 Software Requirements

- 🧑‍💻 Arduino IDE
- 📚 Adafruit Fingerprint Sensor Library
- ⚙️ Servo Library
- 📟 LiquidCrystal_I2C Library (Optional)

---

## ⚙️ Working Principle

1. 🔋 Power ON the system.
2. 👆 User places a finger on the sensor.
3. 📷 Fingerprint image is captured.
4. 🔍 Arduino compares the fingerprint with stored templates.
5. ✅ If matched:
   - 🟢 Green LED turns ON
   - 🔔 Buzzer beeps
   - 🚪 Door unlocks
   - ⏳ Waits for 5 seconds
   - 🔒 Door locks automatically
6. ❌ If not matched:
   - 🔴 Red LED turns ON
   - 🚨 Buzzer sounds
   - 🚫 Access denied

---

## 🔌 Pin Connections

| Component | Arduino Pin |
|-----------|-------------|
| 👆 Fingerprint TX | D2 |
| 👆 Fingerprint RX | D3 |
| ⚙️ Servo Motor | D9 |
| 🟢 Green LED | D6 |
| 🔴 Red LED | D7 |
| 🔔 Buzzer | D8 |
| ⚡ VCC | 5V |
| 🌍 GND | GND |

---

## 📁 Project Structure

```text
Fingerprint-Door-Unlock-System/
│
├── 📄 README.md
├── 📄 Fingerprint_Door_Unlock.ino
├── 📄 Fingerprint_Enroll.ino
├── 📂 images/
│   ├── 🖼️ circuit_diagram.png
│   ├── 🖼️ block_diagram.png
│   └── 🖼️ prototype.jpg
├── 📂 docs/
│   ├── 📘 Project_Report.pdf
│   └── 📙 Presentation.pptx
└── 📜 LICENSE
```

---

## 🚀 Applications

- 🏠 Smart Home Security
- 🏢 Office Access Control
- 🧪 Laboratories
- 🏦 Banks
- 🖥️ Server Rooms
- 🏫 Colleges
- 🏨 Hotels
- 🔐 Restricted Areas

---

## 📈 Future Enhancements

- 📶 Wi-Fi Monitoring using ESP32
- 📱 Mobile App Control
- ☁️ Cloud-Based Access Logs
- 📩 SMS Alert using GSM
- 😊 Face Recognition
- 🏷️ RFID + Fingerprint Authentication
- 🔑 OTP-Based Verification

---

## 📚 Learning Outcomes

- 💡 Embedded Systems
- 💻 Embedded C Programming
- 🔄 UART Communication
- 👆 Biometric Authentication
- ⚙️ Servo Motor Control
- 🔌 Relay Interfacing
- 🧩 Sensor Integration
- 🛠️ Hardware Debugging

---

## 👨‍💻 Author

**Karthikeyan J**

🎓 B.E. Electronics and Communication Engineering

💼 Embedded Systems | Embedded C | IoT | Arduino | Firmware Development

---

## 📄 License

📚 This project is developed for **educational and learning purposes**.

⭐ **If you found this project useful, don't forget to Star ⭐ the repository!**
