
# 💳 Online Payments Fraud Detection using Machine Learning

## 📌 Project Overview

This project is a Machine Learning based web application designed to detect fraudulent online payment transactions. The system performs data preprocessing, exploratory data analysis (EDA), model training using XGBoost, and deployment through a Flask web application for real-time fraud prediction.

The main objective is to analyze transaction behaviour and classify whether a payment is **Fraud** or **Legitimate**.

---

## 🧠 Project Workflow (System Flow)

```
Dataset → Data Preprocessing → Feature Engineering → Model Training (XGBoost)
        → Model Saving (payments.pkl) → Flask Web App → User Input → Prediction Output
```

### 🔹 Training Flow

1. Dataset loaded from `data/`
2. Data cleaning and encoding
3. EDA visualizations saved into `training/plots/`
4. Model training using XGBoost
5. Trained model saved as `payments.pkl`

### 🔹 Web Application Flow

1. User opens Flask website
2. Enters transaction details
3. Flask loads trained model
4. Model predicts Fraud / Not Fraud
5. Result shown on UI

---

## 🚀 Features

* Data preprocessing and feature engineering
* Exploratory Data Analysis (EDA)
* Machine Learning model training
* Model persistence using Pickle
* Flask-based prediction interface
* Simple Bootstrap frontend UI

---

## 📂 Project Structure

```
Project-Files/
│
├── flask/
│   ├── templates/
│   │   ├── home.html
│   │   ├── predict.html
│   │   └── submit.html
│   └── app.py
│
├── training/
│   ├── plots/
│   └── train_model.py
│
├── requirements.txt
├── project requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone Repository:

```bash
git clone https://github.com/Madhumitha0027/Online-Payments-Fraud-Detection-using-Machine-Learning.git
cd Online-Payments-Fraud-Detection-using-Machine-Learning
```

Install Dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### 🔹 Step 1 — Train Model

```bash
python training/train_model.py
```

Output:

* EDA plots generated
* Model trained
* `payments.pkl` file created

---

### 🔹 Step 2 — Run Flask Application

```bash
cd flask
python app.py
```

Open Browser:

```
http://127.0.0.1:5000/
```

---

## 🤖 Machine Learning Models

* Random Forest Classifier
* Decision Tree Classifier
* Extra Trees Classifier
* Support Vector Machine
* ⭐ XGBoost (Final Model)

---

## 🛠️ Technologies Used

* Python
* Pandas & NumPy
* Scikit-learn
* XGBoost
* Matplotlib & Seaborn
* Flask
* Bootstrap 5

---

## 📈 Results

The trained XGBoost model shows strong performance in detecting fraudulent transactions.
Evaluation metrics such as Accuracy Score, Confusion Matrix, and Classification Report are displayed during training.

---

## 🎯 Future Improvements

* Deploy application to cloud
* Add authentication system
* Improve UI dashboard
* Real-time API integration

---
