# 🌱 IoT Smart Agriculture Monitoring System

## Overview

The IoT Smart Agriculture Monitoring System is a smart farming solution developed using Python, SQLite, Streamlit, Pandas, and Plotly.

The system simulates agricultural IoT sensors such as:

- Soil Moisture Sensor
- Temperature Sensor
- Humidity Sensor
- Water Level Sensor

Based on sensor readings, the system automatically determines irrigation requirements and displays insights through an interactive dashboard.

---

## Features

✅ Soil Moisture Monitoring

✅ Temperature Monitoring

✅ Humidity Monitoring

✅ Water Level Monitoring

✅ Automatic Pump Control Logic

✅ SQLite Database Integration

✅ Interactive Streamlit Dashboard

✅ Plotly Analytics Charts

✅ Alert Generation

✅ CSV Export Functionality

---

## Technology Stack

- Python 3.12
- SQLite
- Streamlit
- Pandas
- Plotly

---

## Project Architecture

Sensors
↓
Sensor Data Simulation
↓
Threshold Evaluation
↓
Irrigation Logic
↓
SQLite Database
↓
Dashboard Analytics
↓
Alerts & Reports

---

## Folder Structure

IoT-Smart-Agriculture-Monitoring-System/

├── app.py

├── database.py

├── export_csv.py

├── view_data.py

├── requirements.txt

├── README.md

├── .gitignore

├── dashboard/

│ └── dashboard.py

├── data/

│ ├── farm.db

│ └── sensor_report.csv

├── docs/

│ └── project_report.md

└── images/

├── dashboard_final.png

├── soil_moisture_graph.png

├── temperature_graph.png

├── alerts.png

└── project_structure.png

---

## Installation

### Clone Repository

git clone YOUR_GITHUB_LINK

cd IoT-Smart-Agriculture-Monitoring-System

### Install Dependencies

pip install -r requirements.txt

---

## Run Database

python database.py

---

## Generate Sensor Data

python app.py

---

## Run Dashboard

streamlit run dashboard/dashboard.py

---

## Export CSV Report

python export_csv.py

---

## Screenshots

### Dashboard Overview

![Dashboard](images/dashboard_final.png)

### Soil Moisture Analytics

![Soil Moisture](images/soil_moisture_graph.png)

### Temperature Analytics

![Temperature](images/temperature_graph.png)

### Alert System

![Alerts](images/alerts.png)

---

## Learning Outcomes

- IoT System Design
- Sensor Data Simulation
- Automation Logic
- Database Management
- Dashboard Development
- Data Analytics
- Smart Agriculture Concepts

---

## Future Enhancements

- ESP32 Integration
- MQTT Communication
- ThingSpeak Integration
- Blynk Dashboard
- Cloud Deployment
- AI-based Irrigation Prediction

---

## Author

Sharvari Patangrai

Mechanical Engineering Student

IoT & Data Analytics Enthusiast
