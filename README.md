# AI-Driven-Personalized-Nutrition-Health-Platform
🧠 AI-Driven Personalized Nutrition & Health Platform

An end-to-end AI-powered web application that provides personalized diet and health recommendations based on a user’s profile, medical history, and fitness goals.
Built with a Next.js frontend, Flask backend, and PostgreSQL database, the platform integrates machine learning and Google Generative AI to deliver actionable insights and real-time health guidance.

🚀 Features

🧍‍♀️ User Health Profile: Collects and stores data like age, BMI, weight, medical conditions, and allergies.

🍽 Personalized Meal Planner: Suggests healthy meals based on user health data and nutrition goals.

📊 Interactive Dashboard: Visualizes BMI trends and nutrition data using Recharts.

🔐 Secure Authentication: JWT-based login/register system with encrypted credentials.

💬 AI Health Assistant: Uses Google Gemini API for chat-based nutrition guidance and recommendations.

⚙️ Machine Learning Integration: Uses trained models (via Joblib) for health risk and BMI prediction.

🏗️ Tech Stack

Frontend:

Next.js (React, TypeScript)

Tailwind CSS

Axios, Recharts, Framer Motion

Backend:

Flask, Flask-SQLAlchemy

PostgreSQL

Flask-JWT-Extended, Flask-Bcrypt

Joblib (ML model integration)

Google Generative AI API

🧩 Architecture Overview
Frontend (Next.js)  →  Flask REST API  →  PostgreSQL Database
                           ↓
                   Machine Learning Model (Joblib)
                           ↓
                   Google Generative AI (Gemini)

⚡ Installation
1. Clone the repository
git clone https://github.com/anaggha30/AI-Driven-Personalized-Nutrition-Health-Platform.git
cd AI-Driven-Personalized-Nutrition-Health-Platform

2. Backend Setup
cd backend
pip install -r requirements.txt
python app.py

3. Frontend Setup
cd frontend
npm install
npm run dev


Then open http://localhost:3000

🧠 AI / ML Components

Uses pre-trained models for BMI prediction and nutrition classification

Integrates with Google Gemini API for conversational diet recommendations

Supports real-time health queries through a Flask-based chat endpoint
