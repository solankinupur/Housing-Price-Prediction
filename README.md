
# Housing-Price-Prediction

This project explores the **Ames Housing dataset** to predict sale prices of residential homes using various machine learning models. It was originally part of a Kaggle competition designed to test regression and feature engineering skills.

---

##  Objective

The goal is to build a Predictive model that can predict the **final price of homes** based on various features such as location, size, condition, and amenities.

---

##  Key Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Feature engineering
- Handling missing values and categorical variables
- Model training, tuning, and evaluation
- Model explainability

---

## Dataset

- **Source**: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- **Rows**: 1,460 training samples, 80 test samples
- **Features**: 80 variables describing residential homes in Ames, Iowa

---

## Approach

1. **Data Cleaning**
   - Handled missing values with domain-specific strategies
   - Converted numerical categoricals to strings (e.g., quality, year built bins)
   - Skewness Analysis

2. **Feature Engineering**
   - Created new features 
   - Applied ordinal and one-hot encoding

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

- **Best Model**: Ridge Regression with tuned alpha
- **RMSE**:  0.12 
