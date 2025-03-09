# Indoor-Air-Quality-Monitoring-System
# 🌍 Indoor Air Quality Monitoring System using IoT 🌍

## 🏡 Introduction
Indoor air quality (IAQ) is crucial for maintaining a healthy and comfortable living environment. Poor air quality can lead to respiratory issues, reduced cognitive function, and overall discomfort. To address this, we developed a **Smart Indoor Air Quality Monitoring System** using **IoT technology**. 

Our system continuously monitors indoor air quality, provides real-time updates, and takes automated actions to improve air conditions. It is powered by **ESP32**, equipped with **MQ-9 and MQ-135 sensors**, and programmed using **Python** on **Thonny IDE**. The data is uploaded to **ThingSpeak** for visualization and analysis. 📡📊

## 🌟 Features
### ✅ Real-time Indoor Air Quality Monitoring
- Uses **MQ-9** sensor to detect **carbon monoxide (CO) 🏭** levels.
- Uses **MQ-135** sensor to measure **Air Quality Index (AQI) 🌫️**.

### ✅ Real-Time Data Updates 📡
- Sensor data is collected every **5 seconds** ⏳.
- **ThingSpeak** updates the values every **5 minutes** ⏱️ for real-time monitoring.

### ✅ Smart Response System 🏠⚡
- **LCD Display 📟** shows real-time **CO** and **AQI** values.
- **Buzzer 🔊** activates when AQI exceeds safe limits.
- **Servo Motor 🤖** automatically opens a window to improve ventilation when air quality deteriorates.

### ✅ IoT Integration 🌐
- Data is sent to **ThingSpeak** cloud ☁️ for analysis and visualization.
- Remote monitoring via **web dashboard 🖥️**.

## 🔧 Components Used
### 🔹 Hardware 🛠️
- **ESP32 Microcontroller 🎛️** – Handles data processing and communication.
- **MQ-9 Sensor 🏭** – Detects carbon monoxide levels.
- **MQ-135 Sensor 🌫️** – Measures air quality index.
- **LCD Display (16x2) 📟** – Displays real-time sensor readings.
- **Buzzer 🔊** – Alerts users when air quality drops.
- **Servo Motor 🤖** – Automatically adjusts a window for better ventilation.
- **Power Supply 🔋** – Provides necessary voltage to components.

### 🔹 Software 💻
- **Python 🐍 (Thonny IDE)** – Used for programming ESP32.
- **ThingSpeak 📡** – Cloud platform for real-time data visualization.
- **Arduino IDE (alternative) 🎛️** – For microcontroller programming if needed.

## ⚙️ Working Principle
1. **📡 Data Collection**: 
   - MQ-9 and MQ-135 sensors continuously read **CO and AQI** levels.
2. **🧠 Data Processing**: 
   - The ESP32 processes the sensor data and transmits it to **ThingSpeak**.
3. **📟 Real-Time Monitoring**: 
   - The LCD displays real-time air quality values.
4. **🚨 Automated Response**:
   - If AQI exceeds a predefined threshold:
     - **Buzzer 🔊 alerts occupants**.
     - **Servo motor 🤖 opens the window** for ventilation.
5. **☁️ Cloud Storage & Analysis**:
   - Sensor readings are uploaded to **ThingSpeak** every **5 seconds**.
   - Users can access data remotely via the **ThingSpeak dashboard 🖥️**.

## 🛠️ Installation & Setup
### 1️⃣ Hardware Setup 🏗️
1. Connect **MQ-9 and MQ-135** sensors to the **ESP32 🎛️**.
2. Interface **LCD display 📟** to ESP32.
3. Connect **buzzer 🔊 and servo motor 🤖** to appropriate GPIO pins.
4. Power the circuit using a **5V power source 🔋**.

### 2️⃣ Software Setup 💻
1. Install **Python 🐍 (Thonny IDE)** or **Arduino IDE 🎛️**.
2. Install ESP32 board support in **Arduino IDE** (if used).
3. Install necessary Python libraries:
   ```python
   pip install requests
   pip install thingspeak
   ```
4. Set up **ThingSpeak 📡**:
   - Create a **ThingSpeak account 🧑‍💻**.
   - Create a new **channel 📊** and get **API Keys 🔑**.
   - Configure the ESP32 to send data to **ThingSpeak**.

### 3️⃣ Running the Code 🚀
1. Upload the **Python script 🐍** to ESP32.
2. Power on the device 🔋.
3. Check the **LCD display 📟** for real-time CO and AQI readings.
4. Visit **ThingSpeak Dashboard 🖥️** to monitor air quality remotely.

## 🚀 Future Enhancements
🔹 Integrate **mobile app 📱 notifications** for alerts.
🔹 Add **AI-based 🤖 predictive analysis** for better air quality forecasting.
🔹 Implement **additional sensors 📡** for humidity and temperature monitoring.
🔹 Connect with **home automation 🏠 systems** for better integration.

## 🌍 Conclusion
This IoT-based **Indoor Air Quality Monitoring System** helps maintain healthier indoor environments by providing real-time air quality monitoring and automated responses. The system is cost-effective, scalable, and can be improved with advanced AI-driven insights. 🤖📊

---
### 🌟 How can IoT further enhance indoor air quality control? 🌍
### 🌟 What other smart features would you suggest for our prototype? 💡
---

📌 **Contributors 👥**: [SANDEEP , TUSHAR ,SHRIDHAR , I ]
📌 **GitHub Repository 🔗**: []

#### hashtag#IoT hashtag#IndoorAirQuality hashtag#ESP32 hashtag#ThingSpeak hashtag#Python hashtag#SmartHome hashtag#TechForGood

