
# 🌾 SCARS: Smart Climate Adaptive Roofing System

![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Hardware](https://img.shields.io/badge/Hardware-ESP32--C6%20%7C%20Servo%20Actuators-1f618d?style=flat-square)
![Tech Stack](https://img.shields.io/badge/Tech_Stack-Edge_AI%20%7C%20Embedded_C-6c3483?style=flat-square)
![Connectivity](https://img.shields.io/badge/Connectivity-LoRa%20%7C%206LoWPAN-d35400?style=flat-square)
![Power](https://img.shields.io/badge/Power-Solar_Autonomous-d4ac0d?style=flat-square)
![Competition](https://img.shields.io/badge/Competition-IIT%20Bombay%20e--Yantra-c0392b?style=flat-square)

> **An AI-IoT enabled, solar-powered agricultural roofing infrastructure designed to automate microclimate regulation, precision irrigation, and crop protection.**[cite: 13, 14, 15]

---

## 🎥 Project Demonstration
[![SCARS Project Demonstration](https://img.youtube.com/vi/L1znA-y1FiA/maxresdefault.jpg)](https://youtu.be/L1znA-y1FiA)
*(Click the image above to watch the full technical breakdown and hardware demonstration)*

---

## 🏗️ System Architecture & Hardware
SCARS is designed as a scalable, edge-computed solution to mitigate climate vulnerability and labor shortages in open-field farming[cite: 13, 15]. 

**Core Hardware Components:**
*   **Microcontroller:** ESP32-C6-DEVKITC (Handles edge AI logic and IoT communication)[cite: 13, 14].
*   **Actuation:** Servo/Linear motors for synchronized dynamic panel tilting and sun-tracking[cite: 14, 15].
*   **Sensor Network:** 
    *   Soil Moisture, LDR (Light Intensity), Rainfall, Nutrient, and Pest monitoring sensors[cite: 13, 15].
    *   Wind Anemometer for storm detection[cite: 14].
*   **Power System:** 50W Solar Panels integrated with a battery pack and charge controller for complete energy autonomy[cite: 14].
*   **Irrigation:** Embedded micro-irrigation and fertigation pipelines with solenoid valves and dosing pumps[cite: 13, 15].

<img width="1269" height="673" alt="IMG-20251108-WA0013" src="https://github.com/user-attachments/assets/0f628417-fa30-4c7c-a26f-13f1c3e9e648" />

---

## 🧠 Operational Logic & Modes
The system processes data locally for uninterrupted offline functionality, communicating via LoRa/Wi-Fi to a web dashboard[cite: 13].

### 1. Automatic Mode (Crop-Profile Based)
The system self-regulates based on preloaded thresholds for specific crops (e.g., Wheat, Rice, Sugarcane)[cite: 13, 15].
*   **Smart Irrigation:** Automatically triggers micro-sprinklers when soil moisture deviates below the crop's threshold[cite: 13, 15].
*   **Sunlight & Shade Control:** Flaps dynamically adjust to provide full sun, diffused light, or partial shade to mitigate heat stress and reduce evaporation[cite: 13, 15].
*   **Fertigation:** Applies precise nutrient dosing based on real-time soil nutrient feedback[cite: 13, 15].

### 2. Emergency Hailstorm Defense (Priority Override)
If the rainfall or wind sensors detect extreme weather conditions, the system overrides all other modes. The roofing panels immediately close to form a physical shield over the crops, preventing hailstorm damage[cite: 13, 15]. Once conditions stabilize, normal operations resume[cite: 13, 15].

### 3. Manual Mode
Provides direct user control over irrigation, fertigation, and panel orientation via the IoT web dashboard/mobile app[cite: 13].

---

## 🏆 Credentials & Team
This project was developed for the **e-Yantra Innovation Challenge (eYIC) 2025-26** hosted by IIT Bombay[cite: 16].
*   **Team Members:** Gurkirt Singh, Abhay, Manya, Gurpuneet Singh Hunjan[cite: 14, 16]
*   **Mentorship:** Prof. Chahat Jain[cite: 16]
*   **Certifications:**
    *   [e-Yantra Participation Certificate](./credentials/certi_1383_1367_ok.pdf)[cite: 16]
    *   [IIT Bombay Ideation Workshop Attendance](./credentials/certificate.pdf)[cite: 17]
*   **Full Documentation:** [Read the comprehensive project synopsis here](./docs/Major_Project_Synopsis.pdf)[cite: 14].
