🤔What we do?

Our Project name FarmDrive IoT is an AI-driven mobile agricultural monitoring system designed to support precision farming. The robot is equipped with sensors for soil moisture, temperature & humidity, and light intensity, and is controlled via an ESP32 + Blynk IoT mobile interface. Instead of installing multiple fixed sensors across a farm, the vehicle can move to any location to perform on-site environmental measurements.

All collected data is analyzed through a machine-learning model (XGBoost), providing farmers with real-time plant health assessments, disease risk prediction, and water-usage recommendations.

This project was developed during a 10-day international exchange program in Japan, focused on solving real agricultural challenges through IoT and AI.

🎯 Project Goal

To create convenience and good advice for farmers, which is the use of technology in agriculture more.

🌱 Key Features

- Mobile IoT vehicle for field data collection

- ESP32-based wireless control via the Blynk mobile app

- Multisensor system: Soil moisture, DHT22 (temp/humidity), LDR (light)

- AI analysis using XGBoost
  
- Actionable farming recommendations (watering, disease risk, plant health)

💪 FarmDrive IoT uses a dataset structure like this:

- Temperature

- Humidity

- Light intensity

- Soil moisture

- Labels (Ground Truth):

  - Plant health (“Good”, “Medium”, “Poor”)

  - Disease risk (“Low”, “Medium”, “High”)

  - Water needed (e.g., 150ml, 200ml, 248ml)

We chose XGBoost because:

- High accuracy
   
- Works great even with medium-sized datasets

- Can handle missing or noisy sensor inputs

🧠 AI Workflow   

Sensors → ESP32 → Raw Data → AI Model (XGBoost) →   3 Predictions: Plant health, Disease risk, Water requirement     
↓                           
Real-time field measurements     


🧩 Hardware Architecture -> Components Used:

- ESP32 × 2

- L298N Motor driver

- DC Motors & wheels

- Soil moisture sensor

- DHT22 temperature/humidity sensor

- LDR light sensor

- Battery 

- Acrylic + chassis

📱 IoT & Control System

- FarmDrive IoT uses Blynk IoT for:

- Real-time remote control

- Joystick-based navigation

- Live display of sensor values

- Interactive dashboards

- Triggering analysis requests to the AI

📚 Dataset & AI Training Process

- Data collected from field tests in Japan and Thailand

- Stored into Google Sheets automatically

- Cleaned & normalized

- Fed into XGBoost for model training

- Model outputs 3 key predictions

- New readings continue expanding the dataset

- This feedback loop was the biggest breakthrough of the project and enabled our model to reach 92% accuracy in disease-risk prediction.



