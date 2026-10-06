# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting house prices using machine learning techniques.

The project includes data cleaning, exploratory data analysis (EDA), data visualization, categorical feature encoding, regression model training, model evaluation, and feature importance analysis.

---

## 🎯 Objectives

- Clean and preprocess the housing dataset
- Handle missing values
- Perform exploratory data analysis
- Visualize important relationships
- Encode categorical variables
- Train regression models
- Evaluate models using MAE, RMSE, and R²
- Identify important features affecting house prices

---

## 📊 Dataset

The project uses the Kaggle House Prices dataset.

- Rows: 1460
- Columns: 81
- Target variable: `SalePrice`

`SalePrice` represents the final selling price of each house.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab
- GitHub

---

## 🔄 Project Workflow

### 1. Data Cleaning

Missing values were identified and handled using appropriate methods.

- Categorical missing values were handled using `"None"` or the mode.
- Numerical missing values were handled using `0` or the median.
- `LotFrontage` missing values were filled using neighborhood median values.

After cleaning:

```text
Total missing values: 0
