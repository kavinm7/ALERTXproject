🚦 ALERT X
AI-Powered Traffic Management System for Smarter Urban Mobility
Project Overview
ALERT X: Prism is an advanced AI-driven traffic management system designed to enhance urban mobility by providing real-time traffic monitoring, violation detection, and dynamic signal optimization. Unlike traditional navigation tools, ALERT X leverages live camera feeds, computer vision, and AI analytics to offer precise and actionable insights into traffic conditions.

Key features include:

Real-Time Traffic Monitoring: Utilizes live CCTV feeds to monitor traffic flow and detect anomalies.
Violation Detection: Employs computer vision models to identify traffic violations such as signal jumping and wrong-way driving.
Dynamic Signal Optimization: Adjusts traffic signal timings based on real-time data to alleviate congestion.
Incident Alerts: Sends instant notifications to authorities and nearby vehicles in case of accidents or unusual traffic patterns.
Interactive Mapping: Integrates Leaflet.js to render dynamic maps with overlays for traffic density, violations, and predictive congestion.
The system is built using Samsung SmartThings for IoT integration, Samsung IoT Edge for edge computing, and Samsung Knox for secure device connectivity, ensuring a robust and scalable solution for smart cities.

Key Features
Real-Time Camera Analysis: Accesses live traffic cameras to detect rule violations and monitor traffic conditions.
AI Violation Detection: Uses computer vision and ML models for license plate recognition and behavioral prediction.
Traffic Density Optimization: Adjusts signal timings dynamically using AI-driven density analysis.
Incident Alerts: Automatically notifies nearby authorities in case of accidents or abnormal behavior.
Cloud Dashboard: A centralized interface displaying live analytics, traffic trends, and alerts.
Watermark-Enabled Secure Video Streaming: Ensures tamper-proof footage for verification.
Samsung SmartThings Integration: Syncs edge devices and sensors for efficient traffic signal control.
Tech Stack
Category	Tools / Technologies
Frontend	React.js, Tailwind CSS, Leaflet.js
Backend	Tensorflow
Database	Convex
AI Models	YOLOv8 (for object detection), OpenCV, TensorFlow
Integration	Samsung SmartThings, Samsung Knox, Edge IoT
Version Control	Git + GitHub
Setup & Installation
Follow these steps to set up the project locally:

1️. Clone the repository
git clone https://github.com/krishnakeshab-banik/ALERT-X-Prism.git
cd ALERT-X-Prism
2️. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # For Mac/Linux
venv\Scripts\activate      # For Windows
3️. Install dependencies
pip install -r requirements.txt
4️. Run the project
For backend:

python app.py
For frontend:

cd src
npm install
npm run dev
Now open http://localhost:5173 (or the port shown in your terminal) to view the project in your browser.

Repository Structure
ALERT-X-Prism/
│
├── src/                    # React frontend
│   ├── components/         # UI components
│   ├── assets/             # Images & icons
│   ├── App.jsx             # Main React app
│   ├── index.js
│
├── backend/                # Python backend (Flask / FastAPI)
│   ├── app.py
│   ├── models/
│   ├── utils/
│
├── requirements.txt        # Dependencies
├── Team_ALERTX.pdf         # Supplementary file for submission
├── README.md               # This file
└── .gitignore
Submissions
All related submission resources will be added here:

Project Demo Video: https://drive.google.com/file/d/17UgiLvjcu9XqtCbD3f1DSmCeBNd7Wuye/view?usp=sharing

Presentation / Report: Alert X (Samsung Prism).pptx

Future Scope
Integrating AI prediction to anticipate congestion trends.
Using Samsung Cloud AI services for large-scale video analytics.
Enabling citizen reporting through a mobile app integrated with SmartThings.
Expanding to disaster management and emergency vehicle routing.
Team ALERT X
License
This project is created for the Samsung PRISM Gen AI Hackathon 2025 and is open-source under the MIT License.

