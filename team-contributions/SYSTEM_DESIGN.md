<div align="center">

# 🌱⚡ KHETMITRA
### AI × IoT Smart Farming System

**🌾 Soil → 📟 Sensors → ☁️ Cloud → 🤖 AI → 👨‍🌾 Farmer**

</div>

---

## 🚀 System Snapshot

Soil → Sensors → ESP32 → APIs → AI Engine → Mobile / Web

yaml
Copy code

<p align="center">
  <img src="flow1.png" width="85%">
</p>

---

## ⚡ Flow 1: IoT Data Capture

- 📟 NPK & Moisture sensors capture soil data  
- 🧠 ESP32 aggregates readings  
- 💾 SD Card stores data during offline mode  
- 🔄 Auto-sync when internet returns  

<p align="center">
  <img src="flow2.png" width="85%">
</p>

---

## ☁️ Flow 2: Backend & Data Core

- 🌐 REST APIs receive sensor data  
- ✅ Validation & normalization  
- 🗄️ MongoDB stores time-series data  
- 🔐 Secure access for AI & apps  

<p align="center">
  <img src="flow3.png" width="85%">
</p>

---

## 🤖 Flow 3: AI Decision Engine

- 📊 Soil data → ML models  
- 🧠 Context-aware AI reasoning  
- 🌱 Crop, 💧 irrigation & 🧪 fertilizer advice  

<p align="center">
  <img src="flow4.png" width="85%">
</p>

---

## 🧬 Data Model (ER)

User → Farm → Sensor → SoilReading → Recommendation → SustainabilityScore

yaml
Copy code

---

## 🛠️ Technology Stack

| Layer | Technology |
|-----|-----------|
| IoT | ESP32, NPK Sensors |
| Backend | Node.js, Express |
| Database | MongoDB Atlas |
| AI | TensorFlow, Gemini API |
| Frontend | React, Kotlin |
| Cloud | AWS / Azure |

---

## 📈 Scalability & Reliability

- Stateless backend APIs  
- Horizontal scaling  
- Indexed & sharded database  
- Async AI processing  
- Offline data capture + retry sync  

---

## ✅ Final Outcome

**KhetMitra** is a **scalable, AI-powered, real-world agriculture system** built using actual IoT and cloud workflows.

🌾 *Designed for farmers. Powered by intelligence.*