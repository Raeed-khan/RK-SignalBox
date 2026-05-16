# 🛰️ RK-SignalBox v1.0
> **Developed & Maintained by:** [@Raeed-khan](https://github.com/Raeed-khan)

**RK-SignalBox** is a professional, open-source Wi-Fi auditing and analysis framework designed for the **WEMOS D1 Mini (ESP8266)**. It features a fully interactive and responsive custom OLED menu interface controlled entirely via physical navigation buttons.

---

## 👑 Developer Profile
* **Project Creator:** [Raeed Khan](https://github.com/Raeed-khan)
* **Education:** BBA Student at the **University of Buner**
* **Core Focus:** Advanced Cybersecurity, Ethical Hacking, & Wireless Network Auditing
* **GitHub Official:** [@Raeed-khan](https://github.com/Raeed-khan)

### 🚀 About the Developer
This framework is entirely designed, coded, and maintained by **[Raeed Khan](https://github.com/Raeed-khan)**. Alongside his academic studies in Business Administration at the University of Buner, Raeed has developed deep technical expertise in cybersecurity and network security auditing. This project highlights his passion for hardware hacking and open-source security development.

---

## 🛠️ Hardware Requirements
To build this project, you will need the following components:
* **Microcontroller:** WEMOS D1 Mini ESP8266 *(External Antenna version highly recommended)*
* **Display:** 0.96" I2C OLED Screen (SSD1306)
* **Buttons:** 3x Tactile Push Buttons *(Up, Down, Select)*
* **Prototyping:** Breadboard & Jumper Wires

---

## 🔌 Pin Mapping & Wiring Diagram
Connect the components to your WEMOS D1 Mini using the following pin configuration:

| Component | D1 Mini Pin | GPIO | Description |
| :--- | :---: | :---: | :--- |
| **OLED VCC** | 3V3 / 5V | - | Power Supply |
| **OLED GND** | GND | - | Ground |
| **OLED SCL** | D1 | GPIO 5 | I2C Clock Line |
| **OLED SDA** | D2 | GPIO 4 | I2C Data Line |
| **Button UP** | D5 | GPIO 14 | Menu Navigation Up *(Internal Pull-up)* |
| **Button DOWN** | D6 | GPIO 12 | Menu Navigation Down *(Internal Pull-up)* |
| **Button SELECT** | D7 | GPIO 13 | Click / Confirm Action *(Internal Pull-up)* |

---

## 🚀 Getting Started
Follow these easy steps to get your project up and running:

1. Open the **Arduino IDE** on your PC.
2. Go to **File > Preferences** and add the ESP8266 Board Manager URL:  
   `http://arduino.esp8266.com/stable/package_esp8266com_index.json`
3. Go to **Tools > Board > Boards Manager**, search for `esp8266`, and install it.
4. Open the Library Manager (**Tools > Manage Libraries**), then search for and install:
   * `Adafruit SSD1306`
   * `Adafruit GFX Library`
5. Open `RK-SignalBox.ino`, compile the code, and flash it to your WEMOS D1 Mini!

---

## 📜 Disclaimer & Educational Purpose
This framework is developed **strictly for educational purposes, cyber awareness training, and authorized security testing**. Always obtain explicit, legal permission before scanning or testing networks you do not own. The developer, [Raeed Khan](https://github.com/Raeed-khan), holds no responsibility for any unauthorized usage or misuse of this tool.
