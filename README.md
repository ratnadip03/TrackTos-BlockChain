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
