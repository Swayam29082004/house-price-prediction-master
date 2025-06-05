# 🏡 King County House Price Prediction

This project uses **Linear Regression** and **Gradient Boosting Regressor** to predict house prices in King County, USA. The dataset contains house sale prices for King County, including Seattle.

## 📁 Dataset

- **Source**: [kc_house_data.csv](https://www.kaggle.com/harlfoxem/housesalesprediction)
- **Features**:
  - `price`: Sale price (target)
  - `bedrooms`, `bathrooms`, `sqft_living`, `sqft_lot`, etc.
  - `location`: `lat`, `long`, `zipcode`
  - `condition`, `grade`, `waterfront`, `view`, etc.

---

## 📊 Exploratory Data Analysis (EDA)

Visualizations included:
- Bar plot: Number of bedrooms
- Joint plot: Latitude vs Longitude of houses
- Scatter plots:
  - Price vs Sqft Living
  - Price vs Latitude / Longitude
  - Bedrooms vs Price
  - Waterfront vs Price
  - Zipcode vs Price

---

## ⚙️ Preprocessing

- Dropped unnecessary features like `id`
- Converted `date` feature to binary (0: not 2014, 1: 2014)
- Normalized data using `StandardScaler` for PCA
- Created feature matrix `X` and label vector `y`

---

## 📈 Models Used

### 1. Linear Regression
```python
from sklearn.linear_model import LinearRegression
reg = LinearRegression()
reg.fit(x_train, y_train)
reg.score(x_test, y_test)
