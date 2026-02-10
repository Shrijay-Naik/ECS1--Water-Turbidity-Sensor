# 💧 Water Turbidity Sensor – ECS Project 1

A compact, real-time water quality monitoring system designed to measure water turbidity using an Arduino-based embedded solution. The project provides instant visual feedback on water clarity and supports future scalability for environmental and industrial monitoring applications.

---

## 🚀 Features

### Core Functionality

* **Real-Time Turbidity Measurement**: Continuously measures water clarity using an infrared turbidity probe
* **Arduino-Based Processing**: Analog sensor data processed using Arduino Uno
* **LCD Display Output**: Live turbidity values displayed on a 16×2 I2C LCD
* **Water Quality Classification**: Indicates water condition as *Clear*, *Cloudy*, or *Dirty*
* **Portable Design**: Lightweight and battery-powered for field usage
* **Threshold-Based Alerts**: Supports LED/buzzer alerts for high turbidity levels

---

## 🛠️ Technology Stack

### Hardware

* **Microcontroller**: Arduino Uno
* **Sensor**: Water Turbidity Sensor (Infrared-based)
* **Display**: 16×2 LCD with I2C Interface
* **Power Supply**: 5V Battery / USB Power
* **Additional Components**: Jumper wires, resistors, LEDs

### Software

* **Programming Language**: Embedded C / Arduino C
* **IDE**: Arduino IDE 1.8.19
* **Libraries Used**:

  * `Wire.h`
  * `LiquidCrystal_I2C.h`

---

## 📦 Installation & Setup

### Hardware Connections

* **Turbidity Sensor Output** → Arduino **A0**
* **LCD SDA** → Arduino **A4**
* **LCD SCL** → Arduino **A5**
* **VCC** → 5V
* **GND** → Ground

### Software Setup

1. Install **Arduino IDE**
2. Install **LiquidCrystal_I2C** library via Library Manager
3. Connect Arduino Uno via USB
4. Upload the turbidity sensor code
5. Adjust LCD contrast using onboard potentiometer

---

## 🧪 Working Principle

The turbidity sensor emits infrared light through water and measures the intensity of scattered light caused by suspended particles.

* **Low scattering** → Clear water
* **High scattering** → Dirty water

The Arduino converts this analog signal into a calibrated turbidity value, which is displayed on the LCD in real time.

---

## 🏗️ System Architecture

```
Water Sample
     ↓
Turbidity Sensor
     ↓ (Analog Signal)
Arduino Uno (A0)
     ↓ (Processed Value)
I2C LCD Display
```

---

## 📊 Outcomes

* Successfully measured turbidity across multiple water samples
* Displayed stable and readable real-time values
* Correctly classified water quality levels
* Achieved reliable sensor-to-display integration

---

## 🎯 Benefits

* **Instant Feedback**: Real-time water quality monitoring
* **Cost-Effective**: Affordable components with high utility
* **Portable**: Suitable for on-field testing
* **Educational Value**: Hands-on experience with sensors and embedded systems
* **Scalable Design**: Ready for IoT and wireless upgrades

---

## 🧩 Testing & Troubleshooting

### Tests Conducted

* Sensor calibration using different water samples
* LCD readability and contrast testing
* Power stability testing

### Issues Resolved

* I2C address detection using scanner code
* Library compatibility issues
* LCD contrast tuning via potentiometer

---

## 🔮 Future Enhancements

* IoT integration for remote monitoring
* Cloud-based data logging and analytics
* Wireless communication (Wi-Fi / Bluetooth)
* Waterproof casing for industrial usage
* Mobile application for live monitoring

---

## 📚 Learning Outcomes

* Sensor calibration and analog signal processing
* I2C communication protocol
* Embedded system debugging
* Hardware–software integration
* Team-based project development

---

## 👨‍💻 Team Members

* **Shrijay Naik** – 23BCE8159
* **Aniruddh Dwivedi** – 23BCE8304
* **Yash Chaudhary** – 23BCE8384
* **Supratim Ghosh** – 23BCE8428
* **Janga Thulasi** – 23BEC7104

---

## 📄 Conclusion

The Water Turbidity Sensor project successfully demonstrates an efficient, real-time water quality monitoring system using Arduino. The project meets all ECS Project-1 objectives and has strong potential for real-world environmental and industrial applications. The experience gained enhanced practical understanding of embedded systems, sensors, and system debugging.

---
