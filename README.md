# 🫀 Heart Disease Prediction using Logistic Regression (Framingham Dataset)

This repository demonstrates how to use **Logistic Regression** to predict the risk of developing heart disease using the **Framingham Heart Study** dataset.  
The goal is to classify individuals as **at risk** or **not at risk** based on their health and lifestyle attributes.

---

## 📌 Project Overview
Heart disease remains one of the leading causes of death worldwide.  
Machine learning techniques like **logistic regression** can help identify key factors and predict risks early.  

In this project:
- We use the **Framingham dataset** (a well-known cardiovascular study dataset).
- Preprocess the data by handling missing values and normalizing features.
- Train a **Logistic Regression model**.
- Evaluate its performance using accuracy, confusion matrix, and other metrics.

---

## 📊 Dataset
The **Framingham Heart Study dataset** contains data on cardiovascular risk factors.  
Some of the key features include:
- `age` → Age of the individual  
- `sex` → Male/Female  
- `cigsPerDay` → Cigarettes smoked per day  
- `totChol` → Total cholesterol level  
- `sysBP` & `diaBP` → Systolic & diastolic blood pressure  
- `BMI` → Body Mass Index  
- `heartRate` → Resting heart rate  
- `glucose` → Glucose level  
- `TenYearCHD` → Target variable (1 = develops heart disease in 10 years, 0 = otherwise)

---

## ⚙️ Installation & Setup
Clone this repo and install dependencies:

bash
'''
git clone https://github.com/AtharvaDubey25/heart-disease-prediction-using-logistic-regression.git
cd heart-disease-prediction-using-logistic-regression
pip install -r requirements.txt
'''
