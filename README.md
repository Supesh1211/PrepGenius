# 🚀 PrepGenius

## 📌 Overview

PrepGenius is an intelligent interview coaching system that analyzes user responses and provides structured feedback to improve communication, confidence, and answer quality.
It leverages a microservices architecture using Java and Python to deliver real-time analysis and insights.

---

## 🎯 Key Features

* 🧠 Response Analysis (NLP-based)
* 📊 Confidence & Clarity Scoring
* 🗣️ Filler Word Detection
* ⭐ STAR Method Evaluation (Situation, Task, Action, Result)
* 💡 Personalized Feedback & Suggestions
* 🔁 Improvement Tracking System
* 🎤 Speech-to-Text Support (optional)

---

## 🏗️ Architecture

Frontend → Java Backend (Spring Boot) → Python AI Service (FastAPI)

* **Backend (Java)** handles APIs, user sessions, and database
* **AI Service (Python)** performs text and speech analysis
* **Frontend** displays results and dashboards

---
## ⚙️ Tech Stack

### 🔵 Backend

* Java (Spring Boot)
* REST APIs
* MySQL (or any relational DB)

### 🟢 AI Service

* Python (FastAPI)
* NLP Libraries (TextBlob / NLTK / spaCy)

### 🎨 Frontend (Optional)

* HTML, CSS, JavaScript / React

---

## 📂 Project Structure

PrepGenius/
├── backend/        # Java Spring Boot application
├── ai-service/     # Python FastAPI service
├── frontend/       # UI (optional)
├── docs/           # Documentation
└── README.md

---

## 🔄 Workflow

1. User starts interview session
2. System asks a question
3. User responds (text/voice)
4. Java backend sends response to Python service
5. Python analyzes:

   * Sentiment
   * Filler words
   * STAR structure
   * Confidence score
6. Results returned and displayed on dashboard

---

## ▶️ How to Run

### 🔹 Backend (Spring Boot)

cd backend
mvn spring-boot:run

### 🔹 AI Service (FastAPI)

cd ai-service
pip install -r requirements.txt
uvicorn main:app --reload

---

## 🌟 Future Enhancements

* Real-time interview simulation
* Face emotion detection
* AI-generated model answers
* Role-based interview customization

---
## 👥 Contributors

* Supesh Chavhan (Project Owner)
* Team Members

---

## 📢 Note

This project is built for learning, innovation, and improving real-world interview preparation using modern technologies.
