# 🏦 Bank Customer Churn Prediction using Random Forest

Predicting customer churn is a crucial task for banks to improve customer retention and reduce revenue loss. This project builds a Machine Learning model using the Random Forest algorithm to predict whether a customer is likely to leave the bank based on demographic and financial information.

---

## 📌 Project Overview

This project applies Exploratory Data Analysis (EDA), data preprocessing, feature engineering, and a Random Forest Classifier to identify customers who are likely to churn. The model helps banks understand customer behavior and enables proactive retention strategies.

---

## 🚀 Features

- Data Cleaning
- Missing Value Check
- Duplicate Value Check
- Exploratory Data Analysis (EDA)
- Feature Selection
- Label Encoding
- Train-Test Split
- Random Forest Classification
- Model Evaluation
- Feature Importance Analysis

---

## 📂 Dataset

**Dataset:** Churn Modelling Dataset

**Source:** Kaggle

**Records:** 10,000

**Target Variable:**
- Exited
  - 0 → Customer Stayed
  - 1 → Customer Left

### Features

- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary

Dropped Features:
- RowNumber
- CustomerId
- Surname

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 📊 Exploratory Data Analysis

Performed:

- Dataset Overview
- Data Types
- Missing Value Analysis
- Duplicate Check
- Univariate Analysis
- Bivariate Analysis
- Distribution Plots
- Count Plots
- Box Plots

---

## ⚙️ Data Preprocessing

- Removed unnecessary columns
- Encoded categorical variables using LabelEncoder
- Selected relevant features
- Split dataset into training and testing sets

---

## 🤖 Machine Learning Model

Algorithm Used:

- Random Forest Classifier

Reasons for choosing Random Forest:

- Handles non-linear relationships
- Robust to overfitting
- Works well with mixed data types
- Provides Feature Importance
- High classification performance

---

## 📈 Model Evaluation

Performance evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 📉 Feature Importance

Random Forest provides feature importance scores to identify the most influential factors affecting customer churn.

Important features generally include:

- Age
- Balance
- Geography
- IsActiveMember
- NumOfProducts
- CreditScore

---

## 📁 Project Structure

```
Bank-Customer-Churn-Prediction/
│
├── Churn_Modelling.csv
├── RandomForest.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Bank-Customer-Churn-Prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run

```bash
jupyter notebook
```

or

```bash
python RandomForest.py
```

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
```

Install

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## 🎯 Future Improvements

- Hyperparameter Tuning using GridSearchCV
- Cross Validation
- XGBoost Comparison
- LightGBM Comparison
- SHAP Explainability
- Streamlit Web Application
- Model Deployment using Flask/FastAPI
- Docker Containerization

---

## 📚 Learning Outcomes

- Data Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Classification using Random Forest
- Model Evaluation
- Customer Churn Prediction

---

## ⭐ If you found this project useful, consider giving it a star!
