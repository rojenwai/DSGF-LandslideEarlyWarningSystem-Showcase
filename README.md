<div align="center">

# 🏔️ DSGF-LEWS

### Dynamic Satellite–Ground Fusion Grid-Based Landslide Early Warning System

**Hybrid ML-Based Risk Prediction Using Satellite Intelligence and Adaptive IoT Monitoring**

[![Status](https://img.shields.io/badge/status-showcase-blueviolet?style=for-the-badge)](#repository-notice)
[![License](https://img.shields.io/badge/license-proprietary-red?style=for-the-badge)](#repository-notice)
[![Made with](https://img.shields.io/badge/ML-Hybrid%20Risk%20Engine-orange?style=for-the-badge)](#machine-learning-framework)
[![Connectivity](https://img.shields.io/badge/network-LoRa%20%2F%20Offline--First-2ea44f?style=for-the-badge)](#lora-communication-network)

[![AI Impact Summit India 2026](https://img.shields.io/badge/AI%20Impact%20Summit%20India-2026-9146ff?style=flat-square)](#recognition)
[![TechSprint Manipur 1.0](https://img.shields.io/badge/TechSprint%20Manipur%201.0-Runner--Up-yellow?style=flat-square)](#recognition)
[![ReGen Hackathon 2.0](https://img.shields.io/badge/ReGen%20Hackathon%202.0-First%20Runner--Up-yellow?style=flat-square)](#recognition)

</div>

---

### Highlights

* Hybrid ML-based landslide risk prediction
* Satellite and IoT sensor data fusion
* Geo-spatial grid-based monitoring architecture
* Adaptive sensor deployment framework
* LoRa-enabled edge communication network
* Offline-first operation for remote mountainous regions

### Recognition

* 🏆 Exhibited at AI Impact Summit India 2026
* 🥈 Runner-Up, TechSprint Manipur 1.0
* 🥈 First Runner-Up, ReGen Hackathon 2.0

---

## 🎥 Demonstration

The following demonstration presents the DSGF-LEWS framework, including the satellite-based risk assessment workflow, adaptive sensor deployment strategy, machine learning pipeline, and early warning architecture.

<div align="center">

[![Watch the demonstration video](https://img.shields.io/badge/▶%20Watch%20Video%20Presentation-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/d586gNRXdMg)

</div>

---

## Overview

DSGF-LEWS (Dynamic Satellite–Ground Fusion Grid-Based Landslide Early Warning System) is a novel landslide monitoring and forecasting framework that combines satellite intelligence, machine learning, adaptive IoT sensor deployment, LoRa communication, and edge computing to provide scalable, cost-effective, and reliable landslide early warning capabilities.

Traditional landslide monitoring systems generally rely on either large-scale satellite observations or dense ground sensor deployments. Satellite-only approaches often lack real-time subsurface information, while extensive sensor deployments are expensive and difficult to maintain in mountainous terrain.

DSGF-LEWS introduces a dual-stage risk assessment architecture that leverages the strengths of both approaches. The system first performs large-scale satellite-based risk screening and then selectively deploys ground monitoring resources only where elevated risk is detected.

This significantly reduces infrastructure requirements while improving monitoring precision and operational scalability.

<div align="center">
<img src="images/Picture1.png" width="49%" alt="Grid-based satellite risk overview map" />
<img src="images/Picture2.png" width="49%" alt="Grid-level risk data popup on satellite map" />

<sub>Satellite-based grid overlay showing terrain risk classification (Low / Moderate / High) across a monitored region</sub>
</div>

---

## Problem Statement

Landslides continue to pose a major threat to human lives, transportation networks, public infrastructure, and economic activity in mountainous regions.

Common challenges faced by existing systems include:

* High deployment and maintenance costs
* Poor scalability across large terrains
* Dependence on stable internet connectivity
* Limited real-time monitoring capabilities
* Inefficient allocation of sensing resources
* Delayed warning generation

DSGF-LEWS was developed to address these challenges through intelligent risk prioritization and adaptive sensing.

---

## System Architecture

The framework operates through a hierarchical two-stage architecture.

<div align="center">
<img src="images/System Architecture.png" width="85%" alt="DSGF-LEWS system architecture diagram" />
</div>

### Stage 1: Satellite-Based Risk Screening

The target terrain is divided into geo-spatial grids.

For every grid, environmental and geographical features are extracted from satellite and terrain datasets, including:

* Rainfall Intensity
* Vegetation Index (NDVI)
* Slope
* Elevation
* Soil Moisture
* Soil Type
* Land Cover
* Terrain Characteristics

These parameters are processed using a machine learning model that generates an initial risk score for each grid.

Outputs:

* 🟢 Low Risk
* 🟡 Moderate Risk
* 🔴 High Risk

Only grids classified as elevated risk proceed to Stage 2.

This approach enables large-scale monitoring without requiring physical sensors across the entire landscape.

---

### Stage 2: Adaptive Ground Sensor Monitoring

Grids identified as high-risk receive targeted ground monitoring.

Each sensor node collects:

* Soil Moisture Data
* Ground Vibration Data
* Multi-Axis Tilt Measurements
* Environmental Parameters

Unlike traditional deployments, sensor density is determined dynamically based on:

* Terrain complexity
* Slope characteristics
* Grid size
* Critical infrastructure presence

This adaptive strategy significantly reduces deployment cost while preserving monitoring accuracy.

<div align="center">
<img src="images/Picture4.png" width="90%" alt="Ground sensor monitoring dashboard with near-term landslide warning" />

<sub>Ground sensor monitoring panel showing real-time soil moisture, tilt, vibration, and acceleration readings feeding the risk estimator</sub>
</div>

---

## Machine Learning Framework

### Model 1: Satellite Intelligence Layer

Inputs:

* Rainfall
* NDVI
* Slope
* Elevation
* Soil Moisture
* Land Cover

Outputs:

* Grid-Level Landslide Risk Score

Purpose:

* Large-scale hazard screening
* Risk hotspot identification
* Resource prioritization

---

### Model 2: Ground Intelligence Layer

Inputs:

* Soil Moisture
* Vibration
* Tilt Measurements

Outputs:

* Real-Time Ground Risk Score

Purpose:

* Detection of local instability
* Monitoring of slope movement
* Early identification of failure indicators

---

### Risk Fusion Engine

Both risk scores are combined to generate a final risk assessment.

The fusion engine balances:

* Macro-scale satellite observations
* Micro-scale ground sensor intelligence

This hybrid approach improves forecasting reliability and reduces false positives.

<div align="center">
<img src="images/Picture3.png" width="90%" alt="Live dashboard showing fused satellite and ground risk overview" />

<sub>Live dashboard fusing satellite risk overview with ground sensor deployment status and environmental feature breakdown</sub>
</div>

---

## Geo-Spatial Grid Architecture

The entire study area is partitioned into fixed-resolution monitoring grids.

Each grid is assigned a unique Grid ID (GID).

Benefits include:

* Simplified monitoring
* Efficient data management
* Scalable deployment
* Geographic traceability
* Consistent machine learning inputs

This grid-based design enables monitoring of large mountainous regions while maintaining computational efficiency.

---

## LoRa Communication Network

DSGF-LEWS utilizes a LoRa-based wireless communication infrastructure.

Benefits:

* Long-range communication
* Low power consumption
* Minimal operational cost
* Reliable performance in rugged terrain
* Suitable for remote deployments

Sensor nodes communicate directly with a Grid Gateway responsible for local data aggregation and processing.

---

## Intelligent Grid Gateway

Each monitored region contains a dedicated Grid Gateway.

The gateway performs:

* Sensor communication management
* Data aggregation
* Edge processing
* Risk inference
* Alert generation
* Data synchronization

The gateway serves as the local intelligence hub for each monitored grid.

---

## Offline-First Design

Many landslide-prone regions experience intermittent internet connectivity.

To address this challenge, DSGF-LEWS operates using an offline-first architecture.

Capabilities include:

* Local data storage
* Edge inference
* Local alert generation
* Deferred cloud synchronization

This ensures uninterrupted monitoring even during communication outages.

---

## Alert Generation Framework

The system supports multiple alert levels, escalating from routine monitoring to critical, time-boxed evacuation notices.

<div align="center">

| Level | Description | Example Forecast Window |
|:--|:--|:--|
| 🟢 **Advisory** | Early indications of slope instability | No immediate threat |
| 🟡 **Warning** | Elevated risk requiring increased monitoring | 5–7 days |
| 🔴 **Immediate Evacuation Alert** | Critical risk requiring urgent response | 24–72 hours |
| 🔵 **Progressive Instability Forecast** | Long-term prediction of developing slope failure | Multi-week trend |

</div>

<div align="center">
<img src="images/Picture5.png" width="32%" alt="Stable risk forecast panel - no immediate threat" />
<img src="images/Picture6.png" width="32%" alt="Warning risk forecast panel - 5 to 7 day window" />
<img src="images/Picture7.png" width="32%" alt="Critical risk forecast panel - 24 to 72 hour window" />

<sub>Risk escalation states rendered by the Ground Sensor ML Risk Estimator — from stable conditions to an immediate evacuation-grade forecast</sub>
</div>

---

## Alert Dissemination

Alerts can be delivered through:

* SMS
* Mobile Applications
* Email
* Web Dashboards
* Emergency Control Systems

Notifications can be routed to:

* Local District Administration
* Disaster Management Authorities
* State Control Rooms
* Village Authorities
* Infrastructure Operators

This enables rapid and targeted emergency response.

---

## End-to-End Workflow

<div align="center">
<img src="images/WorkFlow.png" width="90%" alt="DSGF-LEWS end-to-end operational workflow" />
</div>

---

## Key Innovations

| Innovation | Description |
|:--|:--|
| **Satellite-First Risk Screening** | Large geographical areas can be monitored without extensive sensor deployment |
| **Adaptive Sensor Deployment** | Monitoring resources are allocated only where necessary |
| **Dual-Stage Machine Learning** | Two independent machine learning models improve prediction accuracy |
| **Multi-Sensor Fusion** | Combines environmental and physical indicators into a unified risk assessment |
| **LoRa-Based Communication** | Provides long-range connectivity suitable for mountainous terrain |
| **Edge Computing** | Enables local processing and rapid decision-making |
| **Offline Operation** | Maintains functionality without continuous internet access |
| **Grid-Level Intelligence** | Supports scalable monitoring across large regions |
| **Risk Escalation Framework** | Generates context-aware warning levels based on severity |
| **Traceability System** | Every sensor and grid is uniquely identifiable for monitoring and auditing purposes |

---

## Technology Stack

<div align="center">

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Risk%20Prediction-orange?style=flat-square)
![GIS](https://img.shields.io/badge/GIS-Geospatial%20Analysis-2ea44f?style=flat-square)
![Remote Sensing](https://img.shields.io/badge/Remote%20Sensing-Satellite%20Data-0078D4?style=flat-square)
![Edge Computing](https://img.shields.io/badge/Edge%20Computing-Grid%20Gateway-9146ff?style=flat-square)
![LoRa](https://img.shields.io/badge/LoRa-Long%20Range%20IoT-blueviolet?style=flat-square)
![ESP32](https://img.shields.io/badge/ESP32-Sensor%20Nodes-red?style=flat-square)
![Solar](https://img.shields.io/badge/Solar%20Powered-Field%20Deployment-yellow?style=flat-square)

</div>

### Software

* Machine Learning
* Geographic Information Systems (GIS)
* Remote Sensing
* Edge Computing
* Data Analytics
* Dashboard Systems
* Risk Modeling

### Hardware

* ESP32
* LoRa Modules
* Soil Moisture Sensors
* IMU / Tilt Sensors
* Vibration Sensors
* Environmental Sensors
* Solar Power Systems
* Gateway Nodes

---

## Applications

* Landslide Early Warning Systems
* Railway Corridor Monitoring
* Highway Safety Monitoring
* Mountain Infrastructure Protection
* Smart Environmental Monitoring
* Disaster Risk Reduction
* Remote Terrain Surveillance

---

## Project Gallery

Repository assets may include:

* System Architecture Diagrams
* Monitoring Dashboards
* Grid Visualization Models
* Sensor Deployment Illustrations
* Prototype Images
* Hackathon Demonstrations
* AI Summit Showcase Photographs

---

## Repository Notice

> ⚠️ This repository serves as a **public showcase** of the DSGF-LEWS research, architecture, methodology, achievements, and system design.
>
> Source code and implementation details are not publicly available due to ongoing patent filing and intellectual property considerations.

---

## Future Work

* Real-World Field Deployment
* Enhanced Machine Learning Models
* Real-Time Satellite Data Integration
* Drone-Assisted Monitoring
* Predictive Digital Twin Systems
* Government Disaster Management Integration
* Multi-Hazard Risk Assessment Expansion

---

## Contact

<div align="center">

**Rojen Wairokpam**

[![Email](https://img.shields.io/badge/Email-rojenwaipersonal%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rojenwaipersonal@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rojenwai-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rojenwai)

</div>

---

<div align="center">

*DSGF-LEWS demonstrates how satellite intelligence, machine learning, edge computing, and IoT systems can be combined to build scalable and cost-effective disaster early warning solutions for vulnerable mountainous regions.*

</div>
