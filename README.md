# 📊 ML Telecom Churn Prediction

This project uses machine learning techniques to predict customer churn in a telecom company, helping the company identify high-risk customers and reduce churn rates.

---

## 📁 Files in the Repository

- `ML_Telecom_Churn_Prediction_Project.ipynb`: Main Jupyter notebook with complete EDA, preprocessing, model building, and evaluation.
- `Telecom Churn.csv`: Dataset used for the analysis and modeling.
- `README.md`: Project overview and usage instructions.

---

## 🧠 Problem Statement

Customer churn is a critical metric for telecom companies. Losing customers directly impacts revenue. This project aims to:

- Analyze customer behavior
- Identify key churn indicators
- Build a predictive ML model to forecast churn

---

## 📊 Dataset Overview

The dataset includes the following features:

- `Account length`
- `Area code`
- `Customer service calls`
- `International plan`
- `Voice mail plan`
- `Total day/eve/night minutes, calls, and charge`
- `Churn` (Target variable)

---

## 🔍 Exploratory Data Analysis

We explored the data through:

- Summary statistics
- Correlation heatmaps
- Distribution plots
- Churn rate visualizations

Key insight: Customers with more service calls and without voicemail plan churn more frequently.

---

## ⚙️ Preprocessing Steps

- Handled missing values
- Encoded categorical features (`Voice mail plan`, `International plan`)
- Removed multicollinearity using VIF
- Scaled features (if needed)

---

## 🧪 Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

### Evaluation Metrics:
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC

---

## 📈 Best Model Performance

| Model            | Test Accuracy |
|------------------|---------------|
| XGBoost Classifier | **~91%**      |

---

## 📌 Conclusion

- The model successfully identifies churn-prone customers.
- `Customer service calls`, `International plan`, and `Day minutes` are strong predictors of churn.

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/Sharath432/ML-Telecom-Churn-prediction-.git
   cd ML-Telecom-Churn-prediction-
