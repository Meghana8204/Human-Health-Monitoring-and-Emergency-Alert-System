 Human Health Monitoring and Emergency Alert System

An IoT-based mini-project developed during my 6th semester to monitor vital health parameters such as **heart rate**, **body temperature**, and **Oxygen level saturation** in real time. If abnormal values are detected, the system sends an **emergency alert** via a **GSM module** or triggers a buzzer alarm.

---

 Project Objective

To build a real-time health monitoring system that detects emergency health conditions and sends immediate alerts to caregivers using sensors, microcontrollers, and GSM technology.

---

 Components Used

- Arduino Uno / NodeMCU ESP8266  
- Pulse Sensor or MAX30100 – for Heart Rate and SpO2  
- DHT11 or LM35 – for Temperature  
- GSM Module (SIM800L) – to send SMS alerts  
- Buzzer & LED – for local alerts  
- ThingSpeak (optional) – for cloud data monitoring  
- Jumper wires, Breadboard, Power Supply

---

Working Process

1. Sensors continuously collect patient vitals.
2. Microcontroller processes the sensor data.
3. If any value crosses a defined threshold:
   -  Buzzer and LED are triggered.
   -  SMS alert is sent via GSM module.
   -  Data is sent to ThingSpeak for remote viewing.

---

 Emergency Conditions (Example Thresholds)

| Parameter     | Normal Range        | Alert Triggered When...         |
|---------------|---------------------|----------------------------------|
| Heart Rate    | 60–100 BPM          | <50 or >120 BPM                 |
| SpO2 Level    | 95–100%             | <90%                            |
| Temperature   | 36–37.5°C           | <35°C or >38°C                  |

---

##  Features

- Real-time patient monitoring  
- SMS alert using GSM module  
- Local alerts via buzzer and LED  
- Optional cloud data logging with ThingSpeak  
- Cost-effective and easily deployable solution

---

##  What I Learned

- Interfacing biomedical sensors with Arduino  
- GSM module communication and serial debugging  
- Real-time signal processing and threshold logic  
- Basics of IoT-based healthcare and data visualization

---

##  Project Info

- **Semester:** 6th Semester  
-  **Year:** 2024  
-  **Team Size:4 members  
-  **College:** Navkis College of Engineering, Hassan

---

## Source Code

> Code files are not included due to formatting or hardware-only implementation. The project was successfully demonstrated using a real-time circuit.

---

## Future Improvements

- Add fall detection using an accelerometer  
- Mobile app for caregivers to receive alerts  
- Data storage using Firebase or MySQL  
- Voice alerts and auto emergency calling


