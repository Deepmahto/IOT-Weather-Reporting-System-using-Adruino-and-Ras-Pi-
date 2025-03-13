# IoT Weather Reporting System using Arduino and Raspberry Pi

## 📌 Project Description
Keeping track of the weather is a critical task requiring high-speed data collection and coordination between weather tracking and reporting teams. This data is essential for various sectors, including:
- **Public use** – for planning daily activities.
- **Maritime industry** – for ship and sea route planning.
- **Fishing departments** – for monitoring weather conditions.
- **Disaster relief organizations** – for proactive response planning.

This project automates the entire process by **capturing weather data in real-time** and **transmitting it over the internet** using IoT. The system utilizes **Arduino, Raspberry Pi, temperature and humidity sensors, a rain sensor, and an LCD display** to achieve this functionality.

## 🌟 Features
- **Instant Data Capture** – Collects temperature, humidity, and rain detection in real-time.
- **IoT-Based Data Transmission** – Transmits collected data over the internet for remote monitoring.
- **Live Data Display** – Weather data is displayed on an LCD and an online IoT dashboard.
- **Error-Free System** – Eliminates manual intervention, ensuring accuracy.

## 🛠️ Components Used
- **Microcontrollers & Boards**
  - Arduino Uno
  - Raspberry Pi (with built-in Wi-Fi)

- **Sensors**
  - Temperature and Humidity Sensor (DHT11/DHT22)
  - Rain Sensor

- **Display & Circuitry**
  - LCD Display
  - Regulatory Circuitry
  - Switches, LEDs, PCB Board
  - Resistors, Capacitors, Transistors, Cables, and Connectors

## 🔧 Working Principle
1. **Sensor Data Collection:**  
   - The **temperature and humidity sensor** captures environmental temperature and humidity levels.  
   - The **rain sensor** detects precipitation.  

2. **Processing & Transmission:**  
   - The **Arduino Uno** reads sensor data and transmits it to the **Raspberry Pi**.  
   - The **Raspberry Pi**, connected to the internet via Wi-Fi, forwards the data to an **IoT Gecko** server.  

3. **Live Data Monitoring:**  
   - The IoT Gecko server receives the weather data and displays it **live** on a web dashboard.  
   - Users can access this dashboard via any web browser to monitor real-time weather conditions.  

## 🖥️ Software & Libraries Used
- **Arduino IDE** – To program Arduino Uno.
- **Python** – For Raspberry Pi data transmission.
- **IoT Gecko** – Cloud-based IoT platform for live data visualization.
- **Libraries:**
  - `DHT.h` (for temperature and humidity sensor)
  - `Wire.h` (for LCD communication)
  - `Requests` (for sending data to IoT Gecko)

## 🚀 Installation & Setup Guide
1. **Hardware Setup**
   - Connect the sensors and LCD display to the **Arduino Uno**.
   - Connect the Arduino to the **Raspberry Pi** via serial communication.
   - Ensure the **Raspberry Pi** is connected to Wi-Fi.

2. **Software Configuration**
   - Install **Arduino IDE** and upload the sensor reading code to the Arduino.
   - Install required **Python libraries** on the Raspberry Pi:
     ```sh
     pip install requests
     ```
   - Configure **IoT Gecko** to receive and display live data.

3. **Run the System**
   - Power up the system and start the Python script on Raspberry Pi to begin data transmission.

## 📌 Applications
- **Weather Monitoring Stations**
- **Smart Agriculture Systems**
- **Environmental Monitoring**
- **Disaster Prediction & Response**
- **Home Automation & Smart Cities**

