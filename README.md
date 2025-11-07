# 🩺 Health Risk Prediction using Machine Learning

A machine learning project that predicts an individual's **health risk level** (High / Low) based on lifestyle behaviors such as diet, sleep, and exercise habits.  
This project aims to demonstrate the full ML pipeline — from **data preprocessing**, **feature engineering**, and **model comparison** to **optimization and visualization**.

---

## 🧠 Project Overview

This notebook explores how various machine learning models can be applied to **health risk prediction** using a synthetic dataset that simulates lifestyle and health factors.  
The project compares multiple algorithms to determine which performs best in predicting the risk level.

---

## 📊 Dataset Information

**Dataset Source:**  
[GitHub - Lifestyle and Health Risk Prediction Synthetic Dataset](https://github.com/Nah-Null/Dataset_ML_PJ)

**Features include:**
- Age, Gender  
- BMI, Exercise frequency, Sleep hours  
- Sugar intake, Smoking, Alcohol consumption  
- Stress level, Diet balance, etc.

**Target variable:**  
- `health_risk` → *Low risk (0)* / *High risk (1)*

---

## ⚙️ Project Workflow

1. **Data Loading** – Load dataset from GitHub.  
2. **Feature Engineering** – Encode categorical features and generate new numerical features.  
3. **Data Splitting** – Split into training, validation, and test sets.  
4. **Model Training** – Train multiple models (Logistic Regression, Naive Bayes, Decision Tree, KNN).  
5. **Model Comparison** – Evaluate each model using accuracy, precision, recall, F1-score, and ROC-AUC.  
6. **Visualization** – Compare model performance using bar charts.  
7. **Optimization** – Use GridSearchCV to fine-tune the Decision Tree classifier.  
8. **Summary Report** – Summarize dataset, model performance, and best model.

---

## 🤖 Machine Learning Models

| Model | Description |
|:------|:-------------|
| Logistic Regression | Baseline linear model for binary classification. |
| Gaussian Naive Bayes | Probabilistic model assuming feature independence. |
| Decision Tree | Non-linear model with interpretable decision rules. |
| K-Nearest Neighbors | Instance-based learning using feature distance. |

---

## 🧾 Model Evaluation & Results

| Metric | Logistic Regression | Naive Bayes | Decision Tree | KNN |
|:-------|:--------------------:|:------------:|:--------------:|:---:|
| Accuracy | 89% | 85% | **92%** | 87% |
| Precision | 88% | 84% | **93%** | 86% |
| Recall | 90% | 83% | **91%** | 88% |
| F1-Score | 89% | 83% | **92%** | 87% |

> 🏆 **Best Model:** Decision Tree (after hyperparameter tuning)

---

## 🎯 Key Insights

- Lifestyle behavior patterns are strong predictors of overall health risk.  
- Decision Tree model performed best, balancing interpretability and accuracy.  
- Feature engineering (especially encoding of categorical features) significantly improved model performance.  
- Visualization helps explain model differences and performance clearly.  

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/HealthRiskPrediction_ML.git
cd HealthRiskPrediction_ML
