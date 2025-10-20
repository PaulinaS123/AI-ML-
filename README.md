# AI-ML-
Assignment 2 -Linear-Regression for House Price Prediction
Student: Victoria Salomon

## Environment Setup and Libraries
This project applies the principles of the ML lifecycle using a standard Python environment for data science and machine learning.

| Component        | Version         | 
| ---------------- | --------------- | 
| **Python**       | 3.13 (Anaconda) | 
| **Pandas**       | 2.2.3           | 
| **Matplotlib**   | 3.10.0          | 
| **Scikit-learn** | 1.6.1           |

## 📊 Dataset
- **Source:** Kaggle House Prices dataset
- **Target Variable:** SalePrice
- **Features Used:** GrLivArea (Above-ground living area), Has_Basement (engineered feature)

## 🧹 Data Cleaning
- Imputed missing values in `LotFrontage` with median.
- Created binary feature `Has_Basement` from `TotalBsmtSF`.

## ⚙️ Model Training
- Split dataset into 80% training and 20% testing sets.
- Trained Linear Regression model using Scikit-learn.

## 📈 Evaluation
- **MSE:** 3,347,071,273.37  
- **R²:** 0.56

## 📉 Visualization
Scatter plot shows predicted vs. actual Sale Prices with regression line.

## 🔮 Custom Predictions
Two test inputs demonstrate reasonable predictions, showing model functionality.
