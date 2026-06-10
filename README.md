# House Price Prediction

**A complete end-to-end Machine Learning project for predicting California house prices.**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-5C5C5C?style=for-the-badge)

## 📋 Project Overview
This project demonstrates a **professional Machine Learning pipeline** for predicting house prices using the famous California Housing dataset. It covers the full data science lifecycle: from data exploration to model deployment readiness.

## ✨ Key Features
- Comprehensive **Exploratory Data Analysis (EDA)** with insightful visualizations
- Data cleaning, preprocessing and **Feature Engineering**
- Training and comparison of multiple models:
  - Linear Regression
  - Random Forest Regressor
  - XGBoost (Best performing)
- Hyperparameter tuning using GridSearchCV
- Robust model evaluation (MAE, RMSE, R² Score)
- Feature importance analysis

## 🛠️ Technologies Used
- **Python** 3.9+
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

## 📊 Results
- **Best Model**: XGBoost
- **R² Score**: ~0.82 on test set
- **RMSE**: Competitive low error

## 🚀 How to Run
```bash
# Clone the repo
git clone https://github.com/EsmaeliKourosh/ai-ml-python-portfolio.git

cd 01_House_Price_Prediction
pip install -r requirements.txt
jupyter notebook notebooks/house_price_prediction.ipynb
