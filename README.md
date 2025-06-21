# Loan-Default-Prediction
# 💳 Loan Default Prediction Using Machine Learning

Predict whether a customer will default on a loan using financial history and behavior patterns.

---

## 📌 Overview

This project applies **machine learning (XGBoost)** to predict **loan defaults** using client financial data. It includes:

- Model training with **SMOTE** for imbalanced data  
- Feature engineering for better accuracy  
- Explainability with **SHAP values**  
- Web interface using **Flask** or **Gradio**  
- Deployment support (Cloudflare Tunnel for Colab)

---

## 📊 Dataset

- Source: [UCI Credit Card Default Dataset](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)
- Records: 30,000
- Features: 23 financial and demographic attributes
- Target: `DEFAULT` (1 = Default, 0 = No Default)

---

## 🧠 Model Architecture

- **Preprocessing**: StandardScaler, OneHotEncoder  
- **Model**: XGBoostClassifier  
- **Balancing**: SMOTE to handle class imbalance  
- **Pipeline**: Custom sklearn-compatible pipeline  
- **Explainability**: SHAP values + feature importance graphs

---

## 🌐 Web Interface Options

- **Gradio UI** for user-friendly input and predictions  
- **Flask App** with Cloudflare Tunnel for live testing in Colab

---

## 🚀 Getting Started
--**Best when used in Google Colab**--

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/loan-default-prediction.git
cd loan-default-prediction
