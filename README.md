# Indoor-Air-Quality-Analytics-PowerBI
This project is created for learning, portfolio, and demonstration purposes.


## Project Overview
This project demonstrates an **end-to-end IoT data analytics solution** for monitoring **Indoor Air Quality (IAQ)** using simulated sensor data.  
The solution ingests real-time environmental data, stores it in a cloud data warehouse, and visualizes actionable insights using **Power BI**.

The dashboard helps **facility managers, operations teams, and business leaders** understand air quality trends, detect anomalies, and ensure a healthy indoor environment.

---

## Business Objective
- Monitor indoor environmental conditions in real time
- Identify unhealthy air quality levels using KPI thresholds
- Analyze trends, patterns, and correlations across sensors
- Enable data-driven decisions for health & compliance

---

## Key Questions Answered
- Is indoor air quality within safe limits?
- Which parameter (CO, PM10, TVOC, Odor) is impacting AQI the most?
- Are there recurring spikes during specific time periods?
- How does temperature and humidity affect air quality?
- Are there early warning signals before AQI becomes unhealthy?

---

## KPIs Tracked
- Temperature (°C)
- Humidity (%)
- Carbon Monoxide – CO (ppm)
-  PM10 (µg/m³)
- TVOC (ppb)
- Odor Index (0–10)
- Air Quality Index (AQI)

---

## Insights Derived
- Identified periods of **elevated PM10 and TVOC levels**
- Observed **positive correlation between PM10 and AQI**
- Detected **humidity impact on odor intensity**
- Enabled **threshold-based color alerts** for unhealthy conditions
- Provided a **single executive view** for air quality monitoring

---
## Architecture Overview

IoT Sensor (Simulated - Python)
↓
AWS Lambda (Data Processing)
↓
AWS S3 (Raw Data Storage)
↓
Snowflake (Cloud Data Warehouse)
↓
Power BI (Dashboard & Analytics)

---

## Tools & Technologies Used
- **Power BI** – Dashboards & reporting
- **DAX** – Measures, KPIs & time intelligence
- **Data Modeling** – Star schema & relationships
- **Visualizations** – KPI cards, trends, heatmaps
- **Snowflake** – Cloud data warehouse
- **AWS S3** – Raw data storage
- **AWS Lambda** – Serverless data ingestion
- **Python** – Sensor data simulation




## 🏗️ Architecture Overview
