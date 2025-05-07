⚠️ This is a draft README. Still a work in progress!

# 🏡 Housing-Price-Prediction

This project explores the **Ames Housing dataset** to predict sale prices of residential homes using various machine learning models. It was originally part of a Kaggle competition designed to test regression and feature engineering skills.

---

## 📌 Objective

The goal is to build a regression model that can predict the **final price of homes** based on various features such as location, size, condition, and amenities.

---

## 🧠 Key Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Feature engineering
- Handling missing values and categorical variables
- Model training, tuning, and evaluation
- Pipeline building
- Model explainability

---

## 📊 Dataset

- **Source**: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- **Rows**: 1,460 training samples, 80 test samples
- **Features**: 80 variables describing residential homes in Ames, Iowa

---

## 🧪 Approach

1. **Data Cleaning**
   - Handled missing values with domain-specific strategies
   - Converted numerical categoricals to strings (e.g., quality, year built bins)

2. **Feature Engineering**
   - Created new features (e.g., total square footage, age of the home)
   - Applied ordinal and one-hot encoding
   - Scaled numeric features for model compatibility

3. **Modeling**
   - Baseline: Linear Regression
   - Advanced: Ridge, Lasso, XGBoost
   - Hyperparameter tuning using cross-validation

4. **Evaluation**
   - Metrics: Root Mean Squared Log Error (RMSLE)
   - Cross-validation to prevent overfitting
   - Feature importance analysis and residual plots

---

## 📈 Results

- **Best Model**: xx..Ridge Regression with tuned alpha
- **CV RMSLE**: *e.g., xx..0.12* 
- **Insights**:
  - `OverallQual`, `GrLivArea`, and `GarageCars` were top predictors
  - Feature
