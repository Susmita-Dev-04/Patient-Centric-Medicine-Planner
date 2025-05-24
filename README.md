# 🩺 Patient-Centric Medicine Planner with Machine Learning

An intelligent web-based application designed to predict diseases based on symptoms and provide personalized medical recommendations including medications, precautions, diet plans, and workouts. Built using **Python**, **Machine Learning**, and **Flask**, this system aims to assist users in proactive health management.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Architecture](#-project-architecture)
- [How It Works](#-how-it-works)
- [Installation & Setup](#-installation--setup)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)

---

## 📖 Overview

This Patient-Centric Medicine Planner is a healthcare web application that leverages Machine Learning to:
- Predict potential diseases based on user-inputted symptoms.
- Provide detailed medical advice including **precautions**, **medications**, **workouts**, and **diet plans** tailored to the predicted disease.
- Offer a user-friendly interface for self-assessment and wellness planning.

---

## ✨ Features

- 🔍 Symptom-based Disease Prediction
- 💊 Recommended Medicines for the predicted condition
- 🥗 Diet and Nutrition Plan suggestions
- 🧘‍♀️ Workout Routines for better recovery
- 🛡️ Precautions to avoid worsening the condition
- 🌐 Web Interface for easy interaction

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Flask
- **ML Model**: Support Vector Classifier (SVC)
- **Dataset**: Symptom-Disease mappings (custom/preprocessed)
- **Libraries**: Pandas, Scikit-learn, NumPy

---

## 🧠 Project Architecture

📁 Project Folder
│
├── app.py # Main Flask app
├── templates/ # HTML templates
│ └── index.html
│ └── result.html
├── static/ # CSS/JS/images
├── model/ # ML model files
│ └── disease_model.pkl
├── data/ # Dataset
│ └── disease.csv
├── requirements.txt # Python dependencies
└── README.md # Project description


---

## ⚙️ How It Works

1. **User Input**: The user selects or types their symptoms.
2. **Disease Prediction**: The trained ML model processes the input and predicts the most probable disease.
3. **Medical Recommendation**: The system displays relevant data including:
   - Description of the disease
   - Precautions to be taken
   - Suggested medications
   - Diet chart
   - Recommended exercises or workouts
4. **Output Display**: All details are shown in a simple and clear UI for the user.

---

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/patient-centric-medicine-planner.git
   
   cd patient-centric-medicine-planner
