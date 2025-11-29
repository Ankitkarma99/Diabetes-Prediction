# **Diabetes Prediction System**

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-latest-black)](https://flask.palletsprojects.com/)
[![Pandas](https://img.shields.io/badge/Pandas->=2.0-blue)](https://pandas.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/ScikitLearn->=1.3-yellow)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 📌 **Description**

This project is a **Machine Learning–based Diabetes Prediction Web App** built using **Flask**, **Logistic Regression**, and **Scikit-Learn**.
Users can input basic medical parameters, and the app predicts whether the person is **Diabetic** or **Not Diabetic**.

---

## 📁 **Project Structure**

```
├── app.py
├── diabetes.csv
├── home.html
├── index.html
├── single_prediction.html
├── Model
│   ├── ModelForPrediction.pkl
│   └── StandardScaler.pkl
├── requirements.txt
└── Logistic Regression - Diabetes Prediction.ipynb
```

---

## ⚙️ **How It Works**

1. User enters medical values in the form.
2. Values are scaled using **StandardScaler.pkl**.
3. Model (`ModelForPrediction.pkl`) predicts diabetes using Logistic Regression.
4. Output is shown on the result page.

---

## 🚀 **How to Run the Project**

### **1. Clone the repository**

```bash
git clone <your-repo-link>
cd <project-folder>
```

### **2. Create Virtual Environment (optional but recommended)**

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### **3. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **4. Run the Flask App**

```bash
python app.py
```

### **5. Open in Browser**

```
http://127.0.0.1:5000/
```

---

## 📊 **Input Features**

| Feature                  | Description                  |
| ------------------------ | ---------------------------- |
| Pregnancies              | Number of pregnancies        |
| Glucose                  | Plasma glucose concentration |
| BloodPressure            | Diastolic blood pressure     |
| SkinThickness            | Triceps skinfold thickness   |
| Insulin                  | Serum insulin level          |
| BMI                      | Body Mass Index              |
| DiabetesPedigreeFunction | Genetic influence score      |
| Age                      | Age of the person            |

---

## 🧠 **Machine Learning Model**

* **Algorithm:** Logistic Regression
* **Scaler Used:** StandardScaler
* **Training File:** diabetes.csv
* **Notebook:** Logistic Regression - Diabetes Prediction.ipynb

---

## 🖼️ **Screenshots (Optional)**

Add screenshots here (Home page, Prediction page, etc.)

---

## 📜 **License**

This project is licensed under the **MIT License**.

---
