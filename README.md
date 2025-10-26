# 🚨 TrackTots — Emergency IoT Monitoring System with Blockchain

A decentralized, real-time **emergency alert and monitoring system** built using **ESP32 IoT nodes** and the **Stellar Blockchain** for tamper-proof, transparent emergency data logging.

---

## 🌍 Overview

**TrackTots** is designed to detect and report emergencies such as abnormal health conditions, sound disturbances, or manual distress signals from IoT devices in the field.  
Each alert is securely transmitted to a decentralized blockchain network (Stellar Testnet) and displayed on a live **React Dashboard** with **Google Maps** integration.

---

## ⚙️ Tech Stack

### 🧠 Hardware (IoT Layer)
- **ESP32** — Central microcontroller  
- **MAX30100** — Heart rate and SpO₂ sensor  
- **KY-038** — Sound detection sensor  
- **Push Button** — Manual SOS trigger  
- **NEO-6M GPS** — Location tracking  
- **SIM800L GSM** — SMS & mobile data communication  

### 🌐 Software (Cloud & App Layer)
- **Backend:** Node.js + Express + Stellar SDK  
- **Frontend:** React + TailwindCSS + Google Maps API  
- **Blockchain:** Stellar Testnet (via Soroban smart contracts)  
- **Database (optional):** MongoDB or local JSON logs  

---

## 🔐 Key Features

✅ Real-time IoT emergency alerts  
✅ On-chain alert logging (Stellar Testnet)  
✅ Web Dashboard with live map & alert history  
✅ Secure wallet login using Freighter Wallet  
✅ Decentralized data — No single-point failure  
✅ SMS & push-based alerts (via GSM + API)  

---

## 🖥️ System Architecture


ESP32 Sensors → GSM/GPS → Backend (Node.js) → Stellar Blockchain → React Dashboard


- IoT node sends data via GSM/WiFi  
- Backend verifies and stores alert  
- Blockchain stores tamper-proof log  
- Frontend visualizes data in real-time  

---

## 🧩 Folder Structure



tracktots_modern/
│
├── backend/
│ ├── server.js
│ ├── routes/
│ ├── controllers/
│ ├── .env.example
│ └── package.json
│
├── frontend/
│ ├── src/
│ ├── public/
│ ├── .env.example
│ └── package.json
│
└── LICENSE


---

## ⚙️ Installation

### Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/emergency-iot-monitor.git
cd emergency-iot-monitor

Backend setup
cd backend
npm install
cp .env.example .env
npm start

Frontend setup
cd ../frontend
npm install
cp .env.example .env
npm start


Then open 👉 http://localhost:3000

🌐 Environment Variables
Backend .env.example
PORT=8080
STELLAR_SECRET_KEY=SXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
STELLAR_DESTINATION=GXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

Frontend .env.example
REACT_APP_API_URL=http://localhost:8080
REACT_APP_GOOGLE_MAPS_KEY=AIzaXXXXXXXXXXXXXXXXXXXXX

🧱 Blockchain Integration (Stellar)

All emergency alerts are stored as transactions on the Stellar Testnet.

Each alert includes:

Device ID

Timestamp

GPS coordinates

Alert type (Heartbeat anomaly / Sound / Manual SOS)

Use Freighter Wallet to log in and verify your on-chain alert proof.

📍 Dashboard Preview

The React dashboard displays:

Live map with alert markers

Device status indicators

Blockchain transaction details

Timestamped alert history

(Screenshot placeholder — add image here later)

🧾 License

This project is licensed under the MIT License — see the LICENSE
 file for details.

✨ Contributors

Developer: Ratnadeep Ramachandra Gosavi

College: D.Y. Patil College of Engineering and Technology, Kolhapur
Year: 2025
