# 🔊 Ultrasonic Blind Stick using Raspberry Pi Pico

This project is a simple and effective assistive device for visually impaired individuals, built around the Raspberry Pi Pico (or compatible RP2040-based board like the RP2040-Zero). It uses an ultrasonic distance sensor to detect nearby obstacles and triggers a buzzer and an LED alert when objects are detected within a safe range.

---

## 📦 Features

- Distance measurement using HC-SR04
- Visual (LED) and audio (buzzer) feedback when objects are nearby
- Compact PCB design suitable for mounting on a walking stick
- Powered by Raspberry Pi Pico with Micro-USB or USB-C

---

## 🧠 How It Works

The HC-SR04 sensor continuously measures distance. If the measured distance is below a preset threshold (e.g., 25 cm), it activates:

- A buzzer (audio alert)
- An LED (visual cue)

All components are mounted on a compact custom PCB connected to the Raspberry Pi Pico.

---

## 📐 Schematic

![Schematic Diagram](https://hc-cdn.hel1.your-objectstorage.com/s/v3/fe3a28b8bb1ab81fd0af61cd3ecb6ae6f97b7743_screenshot_2025-06-22_185549.png)

---

## 🖼️ PCB Layouts

### Top View  
![PCB Top View](https://hc-cdn.hel1.your-objectstorage.com/s/v3/333e6eff0c515566d48c0da66187a7ec991cf4da_screenshot_2025-06-22_092020.png)

### Bottom View  
![PCB Bottom View](https://hc-cdn.hel1.your-objectstorage.com/s/v3/3423ce96feaa011bdb54dd12b359a1650827f547_screenshot_2025-06-22_092032.png)

---

## 🧱 3D PCB Previews

### View 1 
![3D View 1](https://hc-cdn.hel1.your-objectstorage.com/s/v3/0e6492923c0b4334a5370172a727421a89078905_screenshot_2025-06-22_090013.png)

### View 2  
![3D View 2](https://hc-cdn.hel1.your-objectstorage.com/s/v3/1d9541faad887c45587d91a3a6d619d9a547ec12_screenshot_2025-06-22_090111.png)

### View 3
![3D View 3](https://hc-cdn.hel1.your-objectstorage.com/s/v3/0179fea54b76e8135a3db1295d8814479ea8a4ba_screenshot_2025-06-22_090831.png)

### View 4
![3D View 4](https://hc-cdn.hel1.your-objectstorage.com/s/v3/93e07264e6a03bfe4f453a20a77364da6eff2204_screenshot_2025-06-22_090851.png)


---

## 💾 Files Included

- `BlindStick.kicad_sch` – KiCad schematic
- `BlindStick.kicad_pcb` – KiCad PCB layout
- `gerbers/` – Gerber and drill files ready for fabrication
- `images/` – All rendered images and screenshots
- `README.md` – This file

---

## 🤝 Credits

Designed with [KiCad](https://kicad.org/)  
Made as part of Hack Club's #highway program  

---

## 🧵 Author

**Your Name**  
Slack: `@DevaanshPathak`