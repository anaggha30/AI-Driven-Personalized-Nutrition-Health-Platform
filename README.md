# 🧠 AI-Driven Personalized Nutrition & Health Platform

[![Frontend](https://img.shields.io/badge/Frontend-Next.js-blue?logo=next.js)](https://nextjs.org/)
[![Backend](https://img.shields.io/badge/Backend-Flask-green?logo=flask)](https://flask.palletsprojects.com/)
[![Database](https://img.shields.io/badge/Database-PostgreSQL-blue?logo=postgresql)](https://www.postgresql.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?logo=python)](https://www.python.org/)
[![Made with TypeScript](https://img.shields.io/badge/Made%20with-TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

---

An end-to-end **AI-powered web application** that provides **personalized diet and health recommendations** based on a user’s profile, medical history, and fitness goals.  
Built with a **Next.js frontend**, **Flask backend**, and **PostgreSQL database**, the platform integrates **machine learning** and **Google Generative AI** to deliver actionable insights and real-time health guidance.

---

## 🚀 Features
- 🧍‍♀️ **User Health Profile:** Collects and stores data like age, BMI, weight, medical conditions, and allergies.  
- 🍽 **Personalized Meal Planner:** Suggests healthy meals based on user health data and nutrition goals.  
- 📊 **Interactive Dashboard:** Visualizes BMI trends and nutrition data using Recharts.  
- 🔐 **Secure Authentication:** JWT-based login/register system with encrypted credentials.  
- 💬 **AI Health Assistant:** Uses Google Gemini API for chat-based nutrition guidance and recommendations.  
- ⚙️ **Machine Learning Integration:** Uses trained models (via Joblib) for health risk and BMI prediction.  

---

## 🧰 Tech Stack

### 🖥️ Frontend:
- **Next.js (React, TypeScript)**
- **Tailwind CSS**
- **Axios**, **Recharts**, **Framer Motion**

### ⚙️ Backend:
- **Flask**, **Flask-SQLAlchemy**
- **PostgreSQL**
- **Flask-JWT-Extended**, **Flask-Bcrypt**
- **Joblib** (ML model integration)
- **Google Generative AI API**

---

## 🏗️ Architecture Overview
Frontend (Next.js) → Flask REST API → PostgreSQL Database
↓
Machine Learning Model (Joblib)
↓
Google Generative AI (Gemini)
---

## ⚡ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/anaggha30/AI-Driven-Personalized-Nutrition-Health-Platform.git
cd AI-Driven-Personalized-Nutrition-Health-Platform
**###** ****
**###**
Frontend (Next.js) → Flask REST API → PostgreSQL Database
↓
Machine Learning Model (Joblib)
↓
Google Generative AI (Gemini)


---

## ⚡ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/anaggha30/AI-Driven-Personalized-Nutrition-Health-Platform.git
cd AI-Driven-Personalized-Nutrition-Health-Platform

2️⃣ Backend Setup
cd backend
pip install -r requirements.txt
python app.py

3️⃣ Frontend Setup
cd frontend
npm install
npm run dev


Then open http://localhost:3000

🧠 AI / ML Components

Uses pre-trained models for BMI prediction and nutrition classification

Integrates Google Gemini API for conversational diet recommendations

Supports real-time health queries through a Flask-based chat endpoint
