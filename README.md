# 🚗 Car Auction Price Prediction — Machine Learning Project

This project focuses on predicting the **selling price of auctioned cars** using machine learning.  
A total of **9 regression models** were trained and compared using real-world car auction data to identify the most accurate model.

---

## 📌 Project Overview

Car pricing in auctions varies greatly depending on several factors such as brand, model, year, mileage, engine, condition, and many more.  
This project aims to develop a machine learning model that can accurately estimate the auction price based on these features.

---

## 📂 Dataset

| Detail | Information |
|--------|-------------|
| Dataset Name | USA Cars Dataset |
| Source | Kaggle |
| Rows | 2499 |
| Target Variable | `price` |

**Important Features**
- brand, model, year
- title status, color, state

---

## 🔄 Workflow

1. Data Loading  
2. Data Cleaning & Preprocessing  
   - Removing irrelevant columns  
   - Binary encoding & One-Hot encoding  
   - Feature scaling using StandardScaler  
3. Train-test split (70% — 30%)  
4. Model training using 9 different regressors  
5. Performance evaluation (MAE, RMSE, R²)  
---

## 🤖 Machine Learning Models Used

| Conventional Models | Ensemble / Boosting Models |
|--------------------|-----------------------------|
| Linear Regression | Random Forest Regressor |
| KNN Regressor | Gradient Boosting Regressor |
| MLP Regressor | XGBoost Regressor |
| Decision Tree Regressor | LightGBM Regressor |
| — | CatBoost Regressor |

---

## 📊 Evaluation Metrics

| Metric | Meaning | Goal |
|--------|---------|------|
| **MAE** | Average error in price prediction | Lower = better |
| **RMSE** | Penalizes large prediction errors | Lower = better |
| **R² Score** | Variation explained by model | Higher = better |

---

## 🏆 Key Findings

- **Boosting algorithms (XGBoost, LightGBM, CatBoost)** delivered the **highest accuracy** and lowest error.
- **CatBoost** showed the **best overall balance** across all metrics.
- Traditional models like **Linear Regression & KNN** underperformed due to the nonlinear nature of the dataset.

---

## 🛠 Tech Stack

| Category | Tools |
|----------|--------|
| Language | Python |
| ML Libraries | scikit-learn, XGBoost, LightGBM, CatBoost |
| Data Handling | pandas, numpy |
| Visualization | matplotlib |
| Notebook | Kaggle / Jupyter Notebook |

---
