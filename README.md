# IoT-Based Smart Water Leakage Detection and Monitoring System

## 🚀 Overview
The **IoT-Based Smart Water Leakage Detection and Monitoring System** is designed to catch underground pipeline leaks on day one[cite: 2]. By utilizing a network of low-power sensors, this system shifts municipal water maintenance from a reactive approach to a proactive one, saving thousands of liters of treated water and reducing costly emergency repairs[cite: 2].

**Team:** CYBER SENTINELS[cite: 2]
**Members:** Kalindu Ometh, Sajjana Maharu, Yasitha Buddhima, Lasith Madhusanka[cite: 2]

---

## ⚠️ The Problem
Currently, most municipal water leaks go unnoticed for weeks because they happen underground[cite: 2]. Aging pipes, internal corrosion, and external pressure cause hairline cracks that slowly leak treated water into the soil[cite: 2]. By the time a leak is noticed—usually due to a sinkhole, low water pressure, or surface flooding—the damage is extensive and expensive to fix[cite: 2]. This lost water is known as "non-revenue water" and is a major drain on utility budgets[cite: 2].

## 💡 The Solution
Our system retrofits existing water infrastructure with a continuous monitoring layer[cite: 2]. Instead of waiting for visible damage, the system uses sensor data to identify the physical signs of a leak and estimates its location so crews know exactly where to dig[cite: 2].

### Key Features
*   **24/7 Pipeline Monitoring:** Sensors at junctions and trouble spots constantly measure pressure, flow, and acoustic signals[cite: 2].
*   **Early Anomaly Detection:** A lightweight analytics engine compares incoming live data against historical baselines to flag unusual patterns (e.g., a simultaneous pressure drop and flow spike)[cite: 2].
*   **Targeted Digging:** Cross-references data from neighboring nodes to narrow down the exact pipe segment that is leaking[cite: 2].
*   **Real-Time Alerts:** Operators receive instant notifications via a web dashboard and mobile app, ranked by the severity of the estimated water loss[cite: 2].

---

## 🏗️ System Architecture 
The system is divided into six distinct, modular layers to allow for easy upgrades[cite: 2]:

1.  **Sensing Layer:** Pressure, flow, and acoustic sensors attached to pipeline segments[cite: 2].
2.  **Connectivity Layer:** LoRaWAN/NB-IoT network designed to transmit data from underground nodes without draining battery life[cite: 2].
3.  **Edge Layer:** Microcontroller-based nodes that perform local processing to minimize data transmission[cite: 2].
4.  **Cloud Platform:** Handles data ingestion, storage, and processing, maintaining the historical baselines[cite: 2].
5.  **Analytics Layer:** The anomaly detection engine that checks live readings against normal usage swings[cite: 2].
6.  **Application Layer:** A user-friendly web dashboard and mobile app for tracking network health and dispatching maintenance[cite: 2].

---

## 🎯 Target Audience
*   **Primary:** Municipal water authorities and utility companies aiming to reduce non-revenue water[cite: 2].
*   **Secondary:** City infrastructure planners, public works teams, and on-the-ground maintenance crews[cite: 2].
*   **Beneficiaries:** Local residents and businesses who will experience fewer water outages and stabler water pressure[cite: 2].

## 📈 Go-to-Market Strategy
The project will launch as a pilot program within a single municipal water district[cite: 2]. By proving a reduction in non-revenue water and demonstrating the ease of a battery-powered, retrofit installation, the system can then scale to wider city networks and neighboring municipalities[cite: 2].
