# SEMOS_Project
Smart Energy Monitoring & Optimization System (SEMOS)

A lightweight open-source IoT project for real-time energy monitoring, data logging, and anomaly detection.

SEMOS is a school-level IoT system designed to measure voltage, current, power consumption, temperature, and humidity using an ESP32 microcontroller. Sensor data is transmitted through an MQTT (Mosquitto) broker, stored in a local SQLite database, and visualized with a Python Streamlit dashboard.

The project demonstrates a full end-to-end IoT pipeline — from hardware sensing to data analytics — using only open-source tools.

Key Features

⚡ Real-time energy monitoring using INA219

🌡️ Environmental sensing (temperature & humidity) via DHT22

📡 MQTT communication with Mosquitto

🗃️ Local data storage using SQLite

📊 Interactive dashboard for live charts and insights

🔍 Basic anomaly detection for unusual power usage

✔️ Fully open-source, easy to reproduce, ideal for education

Tech Stack

Hardware: ESP32, INA219, DHT22

Protocols: MQTT (Mosquitto)

Backend: Python, SQLite

Frontend: Streamlit

Analytics: Rule-based + optional ML (IsolationForest)
