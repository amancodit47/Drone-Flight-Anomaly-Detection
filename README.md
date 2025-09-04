# Drone Anomaly Detection 

A comprehensive platform for analyzing drone telemetry data and identifying potential security threats using **multi-dimensional anomaly detection** and **AI-powered analysis**.  

---

## 📌 Overview

This system empowers security professionals and defense teams to **detect suspicious drone activities in real-time**. It combines **statistical detection methods**, **machine learning algorithms**, and **AI interpretation** to provide **actionable intelligence** for mission-critical decisions.  

---

## ✨ Features

- **Multi-dimensional Anomaly Detection**
  - Distance-to-pilot analysis (BVLOS detection)  
  - Speed anomaly detection  
  - Turn rate analysis  
  - Burst detection (sudden flight changes)  
  - Cluster-based anomaly detection (HDBSCAN)  
  - ML-based detection using Isolation Forest  

- **AI-Powered Threat Assessment**
  - Automated risk interpretation using OpenAI’s `o3` model  
  - Threat prioritization (scale 1–5)  
  - Contextual reasoning for anomalies  
  - Actionable response recommendations  

- **Interactive Web Interface**
  - Upload drone telemetry CSV files  
  - Real-time anomaly visualization on map  
  - AI-powered Q&A chat assistant  
  - Export annotated results  

- **Comprehensive Reporting**
  - Threat profiles for anomalous drones  
  - Priority-based sorting of alerts  
  - Detailed rationale behind detection  
  - Contingency action planning  

---

## ⚙️ Installation

### Prerequisites
- Python **3.8+**  
- FastAPI  
- Dependencies listed in `requirements.txt`  
- OpenAI API key  

### Setup
```bash
# Clone the repository
git clone https://github.com/amancodit47/Drone-Flight-Anomaly-Detection.git
cd Drone-Flight-Anomaly-Detection

# Install dependencies
pip install -r requirements.txt
