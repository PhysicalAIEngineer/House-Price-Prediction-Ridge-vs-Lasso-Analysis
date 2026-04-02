# House-Price-Prediction-Ridge-vs-Lasso-Analysis
End-to-end machine learning project for house price prediction using advanced EDA, feature engineering, and regularization techniques. Compared Ridge and Lasso regression with hyperparameter tuning to handle multicollinearity and improve accuracy. Includes business insights for real estate investment decisions.

---

# 🏠 House Price Prediction using Ridge & Lasso Regression

## 🚀 Project Overview

This project builds an end-to-end machine learning pipeline to predict house prices using advanced data analysis, feature engineering, and regularization techniques. The goal is to help real estate companies identify undervalued properties and maximize profit through data-driven decisions.

---

## 🎯 Business Problem

A US-based company (**Surprise Housing**) aims to enter the Australian housing market.
The objective is to:

* Predict the **actual value of houses**
* Identify **undervalued properties**
* Optimize **buy → renovate → sell strategy**

---

## 📊 Dataset

* Housing dataset with multiple features such as:

  * Property size
  * Quality
  * Basement area
  * Garage capacity
  * Year built, etc.

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 🔍 Project Workflow

### 1. Data Understanding & EDA

* Distribution analysis (SalePrice)
* Correlation heatmaps
* Outlier detection (Z-score, IQR)
* Feature relationships (scatter, box plots)

---

### 2. Data Preprocessing

* Missing value treatment
* Feature engineering:

  * Age of house
  * Has basement
  * Large house indicator
* Encoding categorical variables
* Log transformation of target variable

---

### 3. Model Building

#### 🔹 Lasso Regression (L1)

* Feature selection
* Sparse model

#### 🔹 Ridge Regression (L2)

* Handles multicollinearity
* Stable predictions

---

### 4. Hyperparameter Tuning

* GridSearchCV used to find optimal **alpha (λ)**
* Cross-validation (5-fold)

---

### 5. Model Evaluation

* Mean Absolute Error (MAE)
* R² Score
* Train vs Test comparison

---

## 🏆 Results

| Model | MAE      | Performance       |
| ----- | -------- | ----------------- |
| Ridge | ✅ Lower  | Best              |
| Lasso | ❌ Higher | Feature selection |

👉 **Ridge Regression outperformed Lasso** due to high feature correlation.

---

## 📌 Key Insights

* **OverallQual** is the most important feature
* **GrLivArea** strongly impacts price
* **Garage & Basement** add significant value
* Quality improvements → **highest ROI**

---

## 💼 Business Strategy

* Buy **medium-quality houses**
* Improve **quality & functionality**
* Sell at **premium pricing**

> “Value in real estate comes from improving perceived quality, not just size.”

---

## 🧠 Key Learnings

* Importance of feature engineering
* Handling multicollinearity
* Ridge vs Lasso trade-offs
* Real-world ML pipeline design

---

## 📈 Future Improvements

* Add location-based features
* Use advanced models (XGBoost, LightGBM)
* Deploy as web app (Streamlit)

---

## 🤝 Contribution

Feel free to fork, improve, and contribute!

---

## ⭐ Acknowledgment

This project is inspired by real-world business problems in real estate analytics and machine learning.

---

# 🚀 Author

**Chetan Sonigara**
AI Research Engineer | Autonomous Systems | ML Enthusiast

---
