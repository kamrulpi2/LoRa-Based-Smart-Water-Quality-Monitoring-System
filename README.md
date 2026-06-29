# LoRa-Based-Smart-Water-Quality-Monitoring-System
<img width="1882" height="843" alt="Webdashboard" src="https://github.com/user-attachments/assets/98d18797-a8db-46a3-a824-224bf99259b7" />
<img width="1582" height="672" alt="data" src="https://github.com/user-attachments/assets/58d82c36-7f09-4c9f-af29-7d40ff83c8b8" />

The LoRa-Based Smart Water Quality Monitoring System is an IoT solution designed for long-range, real-time monitoring of water quality in rivers, fish farms, reservoirs, lakes, and industrial water systems.

The transmitter node continuously collects sensor data and sends it over a LoRa wireless network to a receiver node. The receiver uses an ESP32 to upload the received data to Firebase Realtime Database via Wi-Fi. A responsive HTML, CSS, and JavaScript dashboard retrieves the data using the Firebase API and displays live graphs, historical trends, alerts, and monitoring information.

🚀 Features
Long-range LoRa communication
Real-time sensor monitoring
Firebase Realtime Database integration
Live web dashboard
Responsive HTML/CSS/JavaScript interface
Historical data visualization
CSV data export
AI Auto Monitoring Mode
Manual Threshold Configuration
Alarm and Warning System
Mobile and Desktop Support
Low Power IoT Architecture

📡 System Architecture
<img width="1408" height="768" alt="Gemini_Generated_Image_qe2wngqe2wngqe2w" src="https://github.com/user-attachments/assets/147f956a-1a5b-4c7f-b7b7-64422da64399" />
Water Quality Sensors
        ↓
Arduino UNO (LoRa TX)
        ↓
LoRa Wireless Communication
        ↓
ESP32 + LoRa RX
        ↓
Wi-Fi
        ↓
Firebase Realtime Database
        ↓
Firebase API
       ↓
HTML + CSS + JavaScript Dashboard
       ↓
Live Monitoring, Charts, Alerts & Analytics

🔧 Hardware Components
<img width="950" height="689" alt="circuit (1)" src="https://github.com/user-attachments/assets/88eaf29e-3432-484c-b476-f3f6171e0cfa" />

Arduino UNO
ESP32 DevKit
LoRa Module (E32/E220/SX1278)
Temperature Sensor
pH Sensor
Dissolved Oxygen Sensor
Water Level Sensor / Float Sensor
TDS Sensor (Optional)
HLK-PM12 Power Supply
Relay Module
Buzzer
Warning Light

💻 Software Stack
Embedded
Arduino IDE
ESP32 Board Package
LoRa Library
Firebase ESP Client

Cloud................

Firebase Realtime Database

Frontend :

HTML5
CSS3
JavaScript
Chart.js
Tailwind CSS
HTML5
CSS3
JavaScript
Chart.js
Tailwind CSS
