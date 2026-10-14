# ♻️ EcoTrack: AI-Powered Smart Bin & Gamified Household Waste Tracker

## 📌 Problem Statement
[cite_start]Households lack visibility and real-time guidance on their plastic consumption, leading to low recycling efficiency and excessive single-use plastic waste[cite: 8, 24]. Most people are unaware of specific plastic resin types (e.g., PET/HDPE vs. non-recyclable multi-layer films) and lack automated sorting mechanisms at home.

## 💡 Solution Overview
[cite_start]EcoTrack is an integrated IoT and AI ecosystem designed to track, sort, and reduce household plastic waste[cite: 16, 25]:
1. [cite_start]**Pre-Disposal Inventory Tracking:** Mobile app scans receipts or packaging using OCR/CV to log purchase dates and resin types[cite: 27].
2. [cite_start]**Automated Sorting Smart Bin:** Multi-compartment bin with proximity detection, CV image classification, and motorized doors[cite: 16, 27].
3. [cite_start]**App-Bin Sync & Fill Alerts:** Ultrasonic sensors monitor compartment levels and notify users when full[cite: 27].
4. [cite_start]**Gamification:** Users earn "Eco-Points" for proper segregation and meeting reduction goals[cite: 27].

## 🛠️ System Architecture & Tech Stack
* [cite_start]**Mobile App:** React Native / Flutter, Python (FastAPI/Flask) [cite: 22, 26]
* [cite_start]**Computer Vision & AI:** OpenCV, YOLOv8 Lite (trained on plastic resin datasets) [cite: 26]
* [cite_start]**Hardware / IoT:** ESP32 / Raspberry Pi, Servo Motors, Ultrasonic Sensors, Camera Module [cite: 26]

## 🚀 Repository Folder Structure
* [cite_start]`/mobile-app` - Cross-platform UI and scanning feature [cite: 9, 21, 50]
* [cite_start]`/backend` - API services and databases [cite: 9, 21, 50]
* [cite_start]`/ai-vision` - Model training and inference scripts [cite: 9, 21, 50]
* [cite_start]`/iot-hardware` - Microcontroller firmware for sensors and motors [cite: 9, 21, 50]
* [cite_start]`/docs` - System diagrams and submission slides [cite: 12, 21, 50]

## 📝 Setup Instructions
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/ecotrack-ai-smartbin.git](https://github.com/your-username/ecotrack-ai-smartbin.git)
