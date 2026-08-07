# 💧 IoT-Based Smart Water Leakage Detection and Monitoring System

**Team CYBER SENTINELS**
*Kalindu Ometh | Sajjana Maharu | Yasitha Buddhima | Lasith Madhusanka*

---

## 📊 Project Presentation
> **Note:** We have included a comprehensive project presentation in this repository. We explain everything about this system's technical architecture, hardware implementation, and go-to-market strategy in detail during that presentation. Please refer to the presentation file for the complete deep-dive into our project.

---

## 📖 Executive Summary
This project is designed to detect underground water pipe leaks immediately, preventing thousands of liters of treated water from being lost before anyone notices. By deploying pressure, flow, and acoustic sensors along pipelines, the system streams continuous data to the cloud. An anomaly detection engine flags irregularities and pinpoints the location for municipal water authorities, allowing for rapid, targeted repairs that reduce non-revenue water waste and lower emergency repair costs.

## ⚠️ The Problem
* **Aging Infrastructure:** Pipes crack and corrode due to age, high water pressure, and the stress of heavy vehicles overhead.
* **Invisible Damage:** Because most pipes are buried under asphalt, leaks can run for days or weeks undetected until residents complain of low pressure or roads sink.
* **Non-Revenue Water:** Utilities spend heavy amounts of money to treat water that is ultimately lost into the ground, heavily impacting their budgets.
* **Reactive Maintenance:** Crews currently rely on visible signs or complaints rather than early detection, leading to larger, more expensive emergency repair jobs and property damage.

## 💡 The Solution
Instead of waiting for visible signs of a leak, this system provides a smart monitoring layer that bolts onto existing infrastructure. 

* **24/7 Surveillance:** Sensor nodes placed at valves, junctions, and known trouble spots constantly monitor the pipeline to eliminate blind spots.
* **Early Anomaly Detection:** A lightweight analytics layer compares live readings against established historical baselines, triggering alerts when unusual patterns occur.
* **Precise Localization:** By cross-referencing data from neighboring sensors on either side of a suspect segment, the system estimates the exact location of the leak to minimize exploratory digging.
* **Instant Alerting:** Operators are immediately notified via a web dashboard and mobile app, with alerts ranked by the severity of the estimated water loss.

## 🏗️ System Architecture
The architecture is divided into six decoupled layers, allowing individual components to be upgraded or swapped independently:

| Layer | Component | Function |
| :--- | :--- | :--- |
| **Sensing** | Pressure, flow, and acoustic sensors | Captures the physical signs of leaks at each pipeline segment. |
| **Edge** | Microcontroller-based sensor nodes | Processes data locally to reduce transmission loads and significantly extend battery life. |
| **Connectivity** | LoRaWAN / NB-IoT | Transmits readings from hard-to-reach or underground nodes using minimal power. |
| **Cloud Platform**| Data ingestion & storage | Centralizes incoming data and maintains historical performance baselines. |
| **Analytics** | Anomaly detection engine | Compares real-time data against normal parameters to flag leaks (e.g., simultaneous pressure drops and flow spikes). |
| **Application** | Web dashboard & mobile app | Displays network health, issues alerts, and assists in maintenance planning and record-keeping. |

## 🔄 Workflow
1. **Data Collection:** Sensor nodes continuously measure pressure, flow, and acoustic signals along the pipeline.
2. **Transmission:** Readings are sent to the cloud via a low-power wide-area network.
3. **Analysis:** The analytics engine evaluates the incoming data against the specific segment's normal baseline.
4. **Localization:** If anomalies are detected, the system cross-references nearby nodes to isolate where the leak probably is.
5. **Alerting:** Notifications are pushed to the operator dashboard and app, tagged by estimated loss.
6. **Resolution & Feedback:** Crews dispatch to the targeted spot for repairs, and the repair outcome feeds back into refining the system's baseline.

## 🎯 Target Market & Go-To-Market Strategy
The primary users are municipal water authorities, utility companies, city infrastructure planners, and ground maintenance crews. The system is designed for affordability and ease of retrofit—utilizing battery-powered nodes that clip onto existing infrastructure without requiring major civil works or ripping up streets. 

The deployment strategy begins with a small, single-district pilot to prove a reduction in non-revenue water and faster detection times. These verified metrics will then serve as the foundation for scaling the system city-wide and expanding to neighboring municipalities.
