
<img width="1428" height="954" alt="image" src="https://github.com/user-attachments/assets/76e53ab1-43f8-4f27-850e-7997b78e43dd" />

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

📷 This is the memory and the best experience during this program



![LINE_ALBUM_ยืมแปะหน่อยนะเบ๊บอ้วน_251114_11](https://github.com/user-attachments/assets/76888f36-d7e9-4eb4-a0d2-1040b2d06bad)
![LINE_ALBUM_ยืมแปะหน่อยนะเบ๊บอ้วน_251114_10](https://github.com/user-attachments/assets/ed3e62d8-0ad1-45d0-876a-52df006ba330)
![LINE_ALBUM_ยืมแปะหน่อยนะเบ๊บอ้วน_251114_9](https://github.com/user-attachments/assets/d89bb22b-ac77-492d-9f73-42ea375bed1a)
![LINE_ALBUM_ยืมแปะหน่อยนะเบ๊บอ้วน_251114_7](https://github.com/user-attachments/assets/3d281481-ecb8-4e83-8081-cc934f19c80d)
![LINE_ALBUM_ยืมแปะหน่อยนะเบ๊บอ้วน_251114_6](https://github.com/user-attachments/assets/09f41e04-31e2-43c2-8170-29d2af5bb931)
![LINE_ALBUM_ยืมแปะหน่อยนะเบ๊บอ้วน_251114_5](https://github.com/user-attachments/assets/936b0e4f-e1b7-49e5-85cd-c86c942863ac)
![LINE_ALBUM_ยืมแปะหน่อยนะเบ๊บอ้วน_251114_4](https://github.com/user-attachments/assets/92c55146-dfad-48fe-854a-487a6b5c283e)
![LINE_ALBUM_ยืมแปะหน่อยนะเบ๊บอ้วน_251114_3](https://github.com/user-attachments/assets/9a547d90-f271-4a46-8eae-635f8ebb7efb)
![LINE_ALBUM_ยืมแปะหน่อยนะเบ๊บอ้วน_251114_2](https://github.com/user-attachments/assets/12b46099-3607-4245-a378-ac14aa3b4c8d)
![LINE_ALBUM_ยืมแปะหน่อยนะเบ๊บอ้วน_251114_1](https://github.com/user-attachments/assets/7b480bad-a563-4c32-9b42-989b53c2db18)
<img width="1108" height="1477" alt="image" src="https://github.com/user-attachments/assets/c3e792c3-2438-474c-bdc8-7e86e7a11ae3" />
