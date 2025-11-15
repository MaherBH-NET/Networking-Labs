# College Lab: Smart Home Network (IoT Automation)

## 🧭 Overview
This lab focuses on designing a **smart home network** using Cisco Packet Tracer IoT components.  
The goal is to integrate traditional home devices with IoT sensors, cloud connection, and automated workflows using home gateway programming.

The lab simulates a realistic smart home setup where devices communicate internally and with the cloud (ThingSpeak server).

---

## ⚙️ Tools Used
- Cisco Packet Tracer  
- IoT Home Gateway  
- IoT Sensors, Actuators, and Smart Devices  
- Cloud Server (ThingSpeak simulation)

---

## 🏠 Network Components

### 🌐 Internet Side
- ThingSpeak cloud server  
- iPhone 11 Pro for remote monitoring/control via the Internet  

### 🏡 Home Network Side
- Wireless router  
- Desktop & laptop  
- Motion alarm  
- Door alarm  
- Siren  
- Additional custom-built IoT automation (self-added, not part of assignment requirements)

---

## 🧩 Key Topics
- IoT device configuration in Packet Tracer  
- Home Gateway programming  
- Wireless LAN setup  
- Smart actuator/sensor triggering  
- Cloud monitoring using simulated ThingSpeak server  
- Internal IoT event logic and automation  

---

## 🔧 Lab Tasks Completed
### 1️⃣ Basic Smart Home Setup
- Connected all standard IoT sensors and alarms  
- Configured wireless access  
- Registered devices to the Home Gateway  

### 2️⃣ Cloud Connectivity
- Simulated a ThingSpeak server  
- Allowed remote monitoring via smartphone  
- Enabled IoT data to be sent to the cloud service  

### 3️⃣ Home Gateway Programming (IoT Logic)
Basic automation rules such as:
- Motion alarm triggers siren  
- Door alarm activates warning lights  

---

## 🛠️ **Extra Features (Self-Added Enhancements)**  
These were not required in the assignment but added to improve realism and complexity:

### 🚗 Smoke-triggered automation system
- Added **two cars** as heat/smoke sources  
- When either car is turned ON → produces smoke  
- Smoke triggers a **Smoke Detector**  
- Smoke Detector activates:  
  - 🔊 Alarm  
  - 🌀 A ventilation **Fan**  
- All actions logged/monitored through the Home Gateway  

This demonstrates advanced IoT logic linking **multiple triggers → multiple actions**, similar to real-world home automation flows.

---

## 🧠 Skills Practiced
- Designing IoT-enabled networks  
- Working with sensors, actuators, and automation rules  
- Using Packet Tracer's Home Gateway logic editor  
- Integrating cloud services with home IoT  
- Building custom multi-device interactions using event-based triggers  

---

## 📂 Files Included
- `Smart-Home-Network.pkt`
