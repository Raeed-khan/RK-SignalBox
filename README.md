# RK-SignalBox v1.0 🛰️
> **Maintained by:** [Raeed Khan](https://github.com/Raeed-Phisher)

RK-SignalBox is an open-source standalone Wi-Fi auditing and analysis tool framework built for the **WEMOS D1 Mini (ESP8266)**. Developed by **Raeed Khan**, it features a fully responsive custom OLED menu interface controlled via physical navigation buttons.

## 👑 Developer Profile
* **Project Creator:** Raeed Khan
* **Academic Background:** BBA Student at the **University of Buner**
* **Field of Interest:** Advanced Cybersecurity, Ethical Hacking, & Wireless Network Auditing
* **GitHub:** [Raeed-Phisher](https://github.com/Raeed-Phisher)

### 🚀 About the Developer
This project is fully designed and written by **Raeed Khan**. Alongside his academic studies in Business Administration at the University of Buner, Raeed has built deep technical expertise and strong skills in cybersecurity and network auditing. This tool represents his dedication to learning hardware security and open-source development.

## 🛠️ Hardware Requirements
* **Microcontroller:** WEMOS D1 Mini ESP8266 (External Antenna version recommended)
* **Display:** 0.96" I2C OLED Screen (SSD1306)
* **Buttons:** 3x Tactile Push Buttons (Up, Down, Select)
* **Breadboard & Jumper Wires**

## 🔌 Pin Mapping (Wiring)
| Component | D1 Mini Pin | GPIO | Description |
|---|---|---|---|
| OLED VCC | 3V3 / 5V | - | Power |
| OLED GND | GND | - | Ground |
| OLED SCL | D1 | GPIO 5 | I2C Clock |
| OLED SDA | D2 | GPIO 4 | I2C Data |
| Button UP | D5 | GPIO 14 | Menu Up (Internal Pull-up) |
| Button DOWN | D6 | GPIO 12 | Menu Down (Internal Pull-up) |
| Button SELECT | D7 | GPIO 13 | Click / Select (Internal Pull-up) |

## 🚀 Getting Started
1. Install **Arduino IDE** on your computer.
2. Add ESP8266 Boards URL in Preferences: `http://arduino.esp8266.com/stable/package_esp8266com_index.json`
3. Install **Adafruit SSD1306** and **Adafruit GFX** libraries via the Library Manager.
4. Open `RK-SignalBox.ino`, compile, and flash to your board!

## 📜 Disclaimer & Purpose
This tool is developed strictly for **educational purposes** and authorized penetration testing. It is designed to help students and security enthusiasts understand wireless vulnerabilities. Always obtain explicit permission before analyzing networks you do not own.
