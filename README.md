# ESP32-S3 Drone Project 🚁

An ultra-compact, low-cost quadcopter platform powered by the **ESP32-S3 microcontroller**.
This project integrates **wireless control, power management, and a full sensing suite** into a **single PCB design**, achieving a robust and manufacturable drone for under **$50 per unit ($32.01)**.

---

## ✨ Features

### 🧠 Core Controller

* **ESP32-S3** microcontroller with **WiFi + Bluetooth** for remote control and telemetry.
* **USB-C** interface for programming and charging.
* **Status LEDs** for debugging and state indication.

### 📡 Wireless Control

* Built-in **WiFi/Bluetooth** communication.
* Custom real-time control protocol.

### 🔋 Power Management

* **350mAh single-cell LiPo battery (1S)**.
* **Integrated charging circuitry** on PCB.
* **TPS5642 buck converter** regulates 3.7–4.2V battery input down to 3.3V.
* **Battery monitoring system** with undervoltage protection for safe operation.

### ⚙️ Motor Control

* **Four brushed DC motors** driven via **low RDS-on MOSFETs**.
* **PWM control** for smooth throttle response.
* Optimized **flyback diode placement** for reduced EMI and motor protection.

### 📊 Sensing Suite

* **BMP390 Barometer** – altitude measurements with ±0.5m accuracy.
* **ICM-42670-P 6-axis IMU** – accelerometer + gyroscope.
* **SPI communication** for fast and reliable sensor data exchange.
* **Sensor fusion algorithm** for stabilization.

### 📐 Compact Design

* **3.2” x 3.2” arms** with a **central PCB hub**.
* **Single-board design** for simplified manufacturing and assembly.
* **Integrated charging system** – no external circuitry required.

---

## ✅ Achieved Milestones

* Full system integration on a **single PCB**.
* Reliable flight stabilization using **sensor fusion**.
* Cost-effective design: **$32.01 BOM cost (under $50 target)**.

---

## 📷 Images & Documentation

### Final Drone Assembly

*(Insert images of the fully assembled drone with wings/propellers here)*

### PCB Layout & Schematic

*(Insert high-resolution images/screenshots of the PCB layout and schematic here)*

---

## 📂 Repository Structure

```bash
├── firmware/          # ESP32-S3 firmware for flight control and wireless comm
├── hardware/          # PCB design files, schematics, layouts
├── docs/              # Images, diagrams, and documentation
└── README.md          # Project overview
```

---

## 🚀 Future Work

* Improve flight algorithms with advanced sensor fusion (Kalman filter / complementary filter).
* Add support for brushless motors + ESCs.
* Expand telemetry features (battery %, orientation, altitude streaming).
* Enhance custom wireless control protocol for lower latency.

---

Would you like me to also **add a wiring diagram block** (using ASCII art or schematic-style markdown) to visually show how the ESP32, sensors, power, and motors connect, so people can understand it even without opening the schematic files?
