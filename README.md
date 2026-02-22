# 💳 Intelligent Online Payment Fraud Detection System

## 📌 Project Overview

This project is a Machine Learning–based web application created to detect fraudulent online payment transactions. It performs preprocessing, analysis, model training, and real-time prediction through a Flask interface.

The main aim is to analyze transaction patterns and classify whether a payment is **Fraudulent** or **Legitimate**.

---

## 🧠 Project Workflow (System Flow)

```
Dataset → Data Cleaning → Feature Processing → Model Training (XGBoost)
        → Model Export (payments.pkl) → Flask Application → User Input → Prediction Result
```

### 🔹 Training Flow

1. Dataset loaded from `data/`
2. Data preprocessing and encoding performed
3. Visualization plots saved into `training/plots/`
4. Multiple models trained and evaluated
5. Final trained model stored as `payments.pkl`

### 🔹 Web Application Flow

1. User opens Flask website
2. Transaction details entered
3. Saved model is loaded
4. Prediction performed
5. Result displayed on interface

---

## 🚀 Features

- Data preprocessing pipeline  
- Feature engineering  
- Exploratory Data Analysis (EDA)  
- Machine learning model training  
- Model saving using Pickle  
- Flask-based prediction system  
- Responsive frontend interface  

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
git clone <your-repository-link>
cd <project-folder-name>
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

**Output**

- Visualization plots generated  
- Model trained successfully  
- `payments.pkl` file created  

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

- Decision Tree Classifier  
- Random Forest Classifier  
- Extra Trees Classifier  
- Support Vector Machine  
- ⭐ XGBoost (Final Model)  

---

## 🛠️ Technologies Used

- Python  
- Pandas & NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib & Seaborn  
- Flask  
- Bootstrap  

---

## 📈 Results

The trained XGBoost model shows strong performance in detecting fraudulent transactions. Evaluation metrics such as Accuracy, Confusion Matrix, and Classification Report are displayed during training for performance assessment.

---

## 🎯 Future Improvements

- Cloud deployment  
- User authentication  
- Enhanced dashboard UI  
- Real-time API integration  

---

## 👨‍💻 Team Members

- Member 1  
- Member 2  
- Member 3  
