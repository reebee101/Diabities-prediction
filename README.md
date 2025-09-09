# 🩺 Diabetes Prediction App

This project is a machine learning-powered web app built with Streamlit. It predicts whether a patient is likely to have diabetes based on key medical inputs such as glucose level, BMI, age, and more.

## 🚀 Features

Interactive web interface using Streamlit.

Input patient details (Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age).

Instant prediction:

🟢 Non-Diabetic

🔴 Diabetic

Displays confidence probability for each prediction.

## ▶️ Run the App
From the project directory, run:
  streamlit run diabitieStreamlit.py

## 🧠 Model Information

Algorithm(s): Logistic Regression, Random Forest, or SVM (depending on your training).

Data Scaling: StandardScaler applied for normalization.

Evaluation Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix.

## 📊 Example Prediction

### Input:

Pregnancies: 2

Glucose: 120

Blood Pressure: 70

Skin Thickness: 25

Insulin: 80

BMI: 28.5

Diabetes Pedigree Function: 0.5

Age: 32

### Output:
🟢 Non-Diabetic (Confidence: 0.78)
