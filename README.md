Hearth is a real-time visual smoke detection system designed for early wildfire identification in remote forested environments. Using machine learning, edge computing, and secure communication protocols, Hearth analyzes live video streams from 360°/PTZ cameras, detects smoke plumes, and sends immediate alerts to authorized personnel.

This project is based on the Hearth Software Requirements Specification (SRS), version 1.0.

---

## 🔥 Project Overview

Wildfires continue to threaten forests, wildlife, property, and human life. Hearth provides an automated, 24/7 monitoring solution that detects smoke early—often before reports from human observers.

Hearth uses:

- **RT-DETR object detection model** for real-time smoke identification  
- **Edge inference** for on-site processing  

The system supports deployment in forested areas across North America and is designed for rugged environments with intermittent connectivity.

---

## 🧠 Core Features

### **1. Real-Time Smoke Detection**
- Processes ≥15 FPS live video feeds
- Provides bounding boxes, timestamps, and metadata

---

## 📡 Operating Environment

Hearth is designed for:

- Remote, forested environments  
- Hardware with limited compute/power  
- Outdoor, weather-resistant installations  
- 24/7 autonomous operation  

---

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|--------------|
| Language | Python 3.x |
| ML / CV | RT-DETR, PyTorch, OpenCV |
