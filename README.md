# 🩺 Diabetes Risk Prediction System

A Machine Learning based web application that predicts the risk of diabetes using patient medical data.

This project uses a trained Support Vector Machine (SVM) model and is deployed using Streamlit for real-time predictions.

---

## 📌 Project Overview

Diabetes is one of the most common chronic diseases worldwide. Early detection can help in better management and prevention of complications.

This application:
- Accepts medical input parameters
- Standardizes the data using a trained scaler
- Uses a trained SVM classification model
- Predicts whether a person is at High Risk or Low Risk of Diabetes

---

## 🧠 Machine Learning Workflow

1. Data Collection (PIMA Indian Diabetes Dataset - diabetes.csv)
2. Data Cleaning & Preprocessing
3. Feature Scaling (StandardScaler)
4. Model Training (Support Vector Machine - SVM)
5. Model Serialization using Pickle
6. Web Deployment using Streamlit

Saved Files:
- `model.pkl` → Trained SVM Model
- `scaler.pkl` → Feature Scaler
- `app.py` → Streamlit Application
- `diabetes.csv` → Dataset

---

## 📊 Input Features Used

The model uses the following medical attributes:

- Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- Body Mass Index (BMI)
- Diabetes Pedigree Function
- Age

---

## 🖥️ Tech Stack

- Python
- NumPy
- Pandas
- Scikit-Learn
- Pickle
- Streamlit

---

## ⚙️ How to Run This Project

## 🖥️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/diabetes-risk-prediction.git
```
### 2️⃣ Go to Project Directory
```bash
cd crop-recommendation-system
```

### 3️⃣ Install Required Libraries
```bash
pip install numpy pandas matplotlib scikit-learn
```

### 4️⃣ Run the Project
```bash
streamlit run app.py
```

## 🛠️ Tools Used
```bash
  PyCharm (IDE)
```
