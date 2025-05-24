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
- [Contributing](#-contributing)
- [Acknowledgments](#-acknowledgments)

---

## 📖 Overview

This Patient-Centric Medicine Planner is a healthcare web application that leverages Machine Learning to:
- Predict potential diseases based on user-inputted symptoms.
- Provide detailed medical advice including **precautions**, **medications**, **workouts**, and **diet plans** tailored to the predicted disease.
- Offer a user-friendly interface for self-assessment and wellness planning.

## Home Page View

![Home-Page](https://github.com/Susmita-Dev-04/Patient-Centric-Medicine-Planner/blob/main/Readme-Resource/Home-Page.png)


---

## 💡 Features

- ✅ Disease prediction from multiple symptoms
- 💊 Suggests medication based on diagnosed disease
- 🧘 Provides personalized workout routines
- 🥗 Recommends diet charts for faster recovery
- 🛡️ Lists disease-specific precautions
- 🌐 Easy-to-use Flask web interface

---

## 🧠 Machine Learning

- **Model**: Support Vector Classifier (SVC)
- **Dataset**: Custom dataset loaded from `datasets/` directory
- **Training Code**: Available in `Medicine Recommendation System.ipynb`
- **Model File**: Stored in `svc.pkl` and `model_reference.pkl`

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Flask
- **ML Model**: Support Vector Classifier (SVC)
- **Dataset**: Symptom-Disease mappings (custom/preprocessed)
- **Libraries**: Pandas, Scikit-learn, NumPy

---

## 🧠 Project Architecture

![Architecture](https://github.com/Susmita-Dev-04/Patient-Centric-Medicine-Planner/blob/main/Readme-Resource/Architecture.png)

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
4. **Output Display(Fimal Report)**: All details are shown in a simple and clear UI for the user.

![Report](https://github.com/Susmita-Dev-04/Patient-Centric-Medicine-Planner/blob/main/Readme-Resource/Report.png)

---

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/patient-centric-medicine-planner.git

   cd patient-centric-medicine-planner

2. **Create and activate a virtual environment**
    ```bash
    python -m venv venv
    #For Windows:
    venv\Scripts\activate
    #For macOS/Linux:
    source venv/bin/activate

3. **Install the dependencies**
    ```bash
    pip install -r requirements.txt

        If requirements.txt is not available, install manually:
    pip install flask scikit-learn pandas numpy
4. **Run the application**
    ```bash
    python main.py
5. **Access the app**
    Open your browser and go to http://127.0.0.1:5000/

## 🤝Contributing

**If you would like to contribute to this project, feel free to follow these simple steps:**

- Fork the repository.

- Clone the forked repository.

- Create a new branch and make your changes.

- Commit and push your changes.

- Open a pull request for review.

**Any kind of contribution is welcome — whether it’s fixing bugs, improving the UI, adding new features, or suggesting ideas to enhance the system.**

## Acknowledgments

I would like to thank my mentors and everyone who supported and encouraged me throughout this project. Special thanks to the open-source community and the tools that made this project possible.

