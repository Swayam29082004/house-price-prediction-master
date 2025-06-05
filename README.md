# 🏠 House Price Prediction Using Machine Learning
_A comparative study of Linear Regression and Gradient Boosting Regression_

---

## 📄 Abstract

This project performs a comparative analysis of **Linear Regression** and **Gradient Boosting Regression** techniques for predicting house prices using the **King County housing dataset**. The goal is to evaluate the performance of both models using R² and RMSE metrics and demonstrate the benefits of advanced ensemble methods in real estate forecasting.

---

## 📊 Dataset

- **Name**: `kc_house_data.csv`
- **Source**: [Kaggle - King County House Sales](https://www.kaggle.com/harlfoxem/housesalesprediction)
- **Size**: 21,613 rows × 21 columns
- **Target Variable**: `price`
- **Features**: `sqft_living`, `bedrooms`, `bathrooms`, `floors`, `zipcode`, `waterfront`, `view`, etc.

---

## 🔍 Problem Statement

Real estate pricing is inconsistent due to varying economic conditions and location preferences. This study aims to build models that **accurately predict house prices** and compare regression techniques in terms of accuracy, complexity, and interpretability.

---

## 🚀 Project Scope

- 🔧 **Data Preprocessing** (missing values, feature selection, normalization)
- 📈 **EDA** using visualizations (scatter plots, heatmaps)
- 🤖 **Model Implementation**: Linear Regression & Gradient Boosting
- ⚙️ **Hyperparameter Tuning**: Grid Search, Cross-validation
- 📊 **Model Evaluation**: MSE, RMSE, R² Score
- 🔁 **Comparative Analysis** of performance, interpretability, scalability

---

## 📉 Limitations

### Linear Regression
- Assumes linear relationships
- Sensitive to outliers
- Multicollinearity issues
- Struggles with non-linear data

### Gradient Boosting
- Computationally expensive
- Sensitive to hyperparameters
- Risk of overfitting
- Less interpretable

---

## 📚 Literature Review Summary

| Feature                     | Linear Regression      | Gradient Boosting Regressor |
|----------------------------|------------------------|------------------------------|
| Interpretability           | High                   | Low                          |
| Complexity                 | Low                    | High                         |
| Handles Non-Linearity      | Poor                   | Excellent                    |
| Speed                      | Fast                   | Slower                       |
| Hyperparameter Tuning      | Minimal                | Extensive                    |
| Overfitting Risk           | High                   | Lower                        |
| Test Score (R²)            | ~0.73                  | ~0.91                        |

---

## 🧪 Model Results

| Model                | R² Score (Test) | RMSE (Approx) |
|---------------------|------------------|----------------|
| Linear Regression   | 0.73             | Varies         |
| Gradient Boosting   | 0.91             | Lower RMSE     |

---

## 📈 Visualizations

- Price vs Square Feet
- Price vs Location (Latitude, Longitude)
- Bedrooms vs Price
- Zipcode vs Price
- Waterfront vs Price

---

## 📌 Future Work

- 🔧 Hyperparameter optimization
- 💡 Feature engineering (e.g., polynomial terms)
- 🧹 Regularization: L1 (Lasso), L2 (Ridge)
- 🌲 Compare with other models: XGBoost, LightGBM
- 🌐 Real-time deployment and streaming data support

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/house-price-prediction.git
   cd house-price-prediction
