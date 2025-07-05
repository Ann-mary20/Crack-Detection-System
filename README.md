# IoT-Based Crack Detection in Civil Engineering Structures

An innovative project aimed at ensuring structural safety and longevity by integrating IoT technology into crack detection systems for infrastructure such as bridges and buildings.

## 📌 Abstract

This project presents a real-time, wireless crack detection system using an ESP8266 microcontroller and an ADXL335 3-axis accelerometer. It is designed to identify abnormal structural vibrations that may indicate crack formation. The system streams live data to the **Blynk IoT platform**, where anomalies trigger instant alerts. This low-cost, scalable solution enables early fault detection, replacing traditional, time-consuming manual inspections.

## 🚀 Features

- 📡 Real-time monitoring of structural vibrations
- 📲 Wireless data transmission using ESP8266 and Blynk
- 📉 Frequency-based anomaly detection algorithm
- 🔔 Instant alert notifications for potential cracks
- 🔋 Low-power and cost-effective hardware
- 📊 Visual dashboard for live data analysis

## 🛠️ Tech Stack

- **Hardware:** ESP8266, ADXL335 Accelerometer, Custom PCB
- **Software:** Arduino IDE, Blynk IoT Platform
- **Communication:** Wi-Fi (ESP8266)

## 🧠 Methodology

1. **Sensing:** ADXL335 captures X, Y, and Z-axis vibrations.
2. **Processing:** ESP8266 digitizes analog signals, applies noise filtering and anomaly detection based on frequency thresholds.
3. **Visualization:** Data is transmitted to the Blynk platform for real-time monitoring and alerting.
4. **Alerts:** System triggers visual and digital alerts when vibration deviates ±4 Hz from the baseline (18.2 Hz).

## 📷 System Architecture

- Custom PCB integrating ADXL335 and ESP8266
- Power Supply: 9V battery with voltage regulator
- Data Logging and Visualization on Blynk Dashboard
- Threshold-based frequency monitoring

## 📈 Results

- Successfully detected simulated cracks in a concrete beam
- Real-time alerts triggered on Blynk when abnormal frequencies observed
- Reliable performance under both static and dynamic loading conditions
- Cost-efficient, scalable, and easily deployable in real-world scenarios

## 🔍 Future Improvements

- Integration with AI/ML models for predictive maintenance
- Support for multiple sensors (e.g., temperature, humidity)
- Expansion into cloud analytics and data logging
- Enhanced low-power optimization for longer deployments

## SetUp Images

![image alt](https://github.com/Ann-mary20/Crack-Detection-System/blob/main/WhatsApp%20Image%202025-07-05%20at%201.45.11%20PM%20(1).jpeg)
![image alt](https://github.com/Ann-mary20/Crack-Detection-System/blob/main/WhatsApp%20Image%202025-07-05%20at%201.45.11%20PM%20(2).jpeg)
![image alt](https://github.com/Ann-mary20/Crack-Detection-System/blob/main/WhatsApp%20Image%202025-07-05%20at%201.45.11%20PM.jpeg)
