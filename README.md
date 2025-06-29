# Sustainable_smart_city
# 🏙 Smart City Assistant

An AI-powered dashboard to monitor and manage sustainability metrics, generate eco-tips, forecast utilities, detect anomalies, and summarize city policies — all tailored for smart urban development.

---

## 📌 Project Overview

### Purpose
To provide a centralized platform for city administrators and citizens to interact with key data points for a smarter, more sustainable city.

### Features
- 🔍 AI Chat Assistant  
- 🌱 Eco Tips Generator  
- 📈 Water & Energy KPI Forecasting  
- ⚠ Anomaly Detection  
- 📊 Sustainability Reports  
- 🗣 Policy Summarization  
- 💬 Citizen Feedback Module  
- ☁ Live Weather Information

---

## 🏗 Architecture

### Frontend (Streamlit)
- Built using Python and Streamlit
- Dynamic pages for various city modules
- Connects with backend APIs for live data

### Backend (FastAPI)
- Hosts endpoints for all features
- Uses HuggingFace APIs and OpenWeatherMap
- Lightweight, scalable, and fast

### Database (Optional)
- Currently stateless (no persistent DB)
- Can be extended with MongoDB for future data storage

---

## ⚙ Setup Instructions

### Prerequisites
- Python 3.9+
- Node.js (if extending with React)
- MongoDB (optional)

### Installation

#### Clone Repository
```bash
git clone https://github.com/your-username/smart-city-assistant.git
cd smart-city-assistant



cd backend
pip install -r requirements.txt
uvicorn main:app --reload

cd frontend
streamlit run app.py


smart-city-assistant/
├── backend/
│   └── main.py              # FastAPI backend
├── frontend/
│   └── app.py               # Streamlit frontend
├── README.md
└── requirements.txt         # Python dependencies

