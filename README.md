# House Prices Prediction using Regression

This project is a machine learning regression task based on the [Kaggle House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) dataset. The goal is to predict the final sale price of residential homes based on various features.

## 📂 Project Structure

- `house-prices-prediction-using-regression.ipynb`: Jupyter notebook with data preprocessing, model training, evaluation, and submission generation.
- `README.md`: Project documentation.

## 🧠 Problem Statement

The objective is to build a predictive model that accurately estimates house sale prices. This is a supervised learning regression problem using real-world housing data.

## ⚙️ Techniques Used

- Exploratory Data Analysis (EDA)
- Data cleaning and imputation
- Feature engineering
- Model training using:
  - Linear Regression
  - Ridge/Lasso Regression
  - Random Forest / XGBoost
- Hyperparameter tuning
- Submission file generation for Kaggle

## ✅ Results

- Best model: Random Forest with GridSearchCV
- Public Kaggle Score: 0.13457

## 🛠️ How to Run

1. Install required Python packages (if running locally):
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn xgboost
