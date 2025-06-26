# 🏡 Housing Price Prediction using Linear Regression

This project implements both **Simple** and **Multiple Linear Regression** to predict housing prices using the **Housing Price Prediction** dataset.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yaswanth-G2004/housing-price-regression/blob/main/linear_regression_task.ipynb)

---

## 📊 Project Overview

This notebook includes:
- Loading and cleaning the dataset
- Performing exploratory data analysis (EDA)
- Implementing **Simple Linear Regression** using the `area` feature to predict `price`
- Implementing **Multiple Linear Regression** using the following features:
  - `area`, `bedrooms`, `bathrooms`, `stories`, `parking`
- Evaluating both models using **MAE**, **MSE**, and **R² Score**
- Plotting the regression line for the simple model
- Interpreting the coefficients from the multiple regression model

---

## 📁 Dataset

- **Name:** Housing Price Prediction Dataset  
- **Source:** [Kaggle - Harish Kumar's Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)  
- **Format:** CSV (`housing.csv`)

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 📈 Model Performance

### Simple Linear Regression (Area → Price):
- **MAE:** *e.g., 570000.0*
- **MSE:** *e.g., 489000000000.0*
- **R² Score:** *e.g., 0.65*

### Multiple Linear Regression (Area + Bedrooms + ... → Price):
- **MAE:** *e.g., 430000.0*
- **MSE:** *e.g., 310000000000.0*
- **R² Score:** *e.g., 0.82*

> (*Replace these with your actual output values if desired.*)

---

## 📌 How to Run

1. Clone this repository or open in [Google Colab](https://colab.research.google.com/github/Yaswanth-G2004/housing-price-regression/blob/main/linear_regression_task.ipynb).
2. Upload or load `housing.csv` in the same directory.
3. Run all cells to reproduce results.

---

## ✅ Conclusion

This project demonstrates how linear regression can be used to predict housing prices based on various features. The **simple linear model** provides a good starting point using only one feature (`area`). However, the **multiple linear regression model** improves prediction accuracy by incorporating additional relevant features such as the number of bedrooms, bathrooms, stories, and parking.

By following standard machine learning steps like data preprocessing, model building, evaluation, and interpretation, this project highlights the practical application of regression techniques on real-world data.

---

## 👨‍💻 Author

**Garikipati Yaswanth**  
Computer Science Engineering Student  
GitHub: [https://github.com/Yaswanth-G2004](https://github.com/Yaswanth-G2004)

---
