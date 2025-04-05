# ai_resume_scanner
# 📄 AI Resume Scanner 🔍 | Java + Machine Learning

An intelligent resume screening tool powered by **Java Spring Boot** and **Python Machine Learning**, built with the vision to bring automation and AI into hiring systems.

---

## 🚀 Overview

This project allows users to **upload resumes (PDFs)** through a Java backend. The resume content is extracted and passed to a **Python ML model**, which classifies it as either:
- ✅ “Good Fit”
- ❌ “Needs Improvement”

All results are stored in a database and can be accessed through a REST API.

> ⚡ Passion Project | 💻 Full Stack | 🇮🇳 Built by a student for Bharat

---

## 🧠 Key Features

- Upload resume via Java Spring Boot REST API
- Extract and preprocess text from PDF using Python
- Train & serve ML model (e.g. Logistic Regression)
- Java ↔ Python API communication (Flask + HTTP request)
- Save prediction and metadata to MySQL/PostgreSQL
- Dockerized for easy deployment

---

## 🔧 Tech Stack

| Part              | Tools Used                            |
|------------------|----------------------------------------|
| Backend (Java)   | Spring Boot, REST APIs, JPA/Hibernate  |
| ML/NLP (Python)  | Scikit-learn, Flask, pandas, NumPy     |
| DB               | MySQL or PostgreSQL                    |
| Deployment       | Docker, Railway/Render (free hosting)  |
| Version Control  | Git + GitHub                           |

---

## 📁 Folder Structure (Planned)

ai-resume-scanner/ ├── backend-java/ # Java Spring Boot app │ └── src/ ├── ml-python/ # Python ML model + Flask API │ └── app.py ├── db/ # SQL scripts or Docker DB config ├── docker-compose.yml └── README.md

