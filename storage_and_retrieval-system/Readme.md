# 🏗️ Automated Storage and Retrieval System (AS/RS) Control Panel

This project involves designing an **electrical control panel** for an Automated Storage and Retrieval System (AS/RS) operating across three rack lines using a single carrier vehicle.

## 🔧 System Overview

- Controlled via **Start** and **Stop** push-buttons.
- **Emergency Stop** immediately deactivates all outputs and locks the system.
- Each rack line has its own **material detection sensor**.
- The **carrier and direction motors** activate only if:
  - The related rack sensor detects material, and
  - The carrier is in its **home/start position**.
- If any **access door is open**, the system will not run and an **alarm light** will activate.
- The **control panel fan** remains **on continuously** while the system is running.

## ⚙️ Components Used

- **PLC:** Siemens **S7-1200**
- **Motor Driver:** **GFD00040S** motor drive
- **Sensors & Actuators:**
  - Material sensors for each rack
  - Direction and carrier motors
  - Door sensor
  - Alarm indicator
  - Panel fan

## 📐 Electrical Design (EPLAN)

The system is fully designed in **EPLAN Electric P8**, including:

- Power distribution
- PLC input/output modules
- Wiring for push-buttons and sensors
- Motor drivers and actuator connections
- Safety elements (emergency stop, door interlock)


