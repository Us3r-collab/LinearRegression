# Multiple Linear Regression: Scikit-Learn vs. From Scratch

An end-to-end implementation of **Multiple Linear Regression** in Python. This project demonstrates model building first using **`scikit-learn`**, followed by a **from-scratch implementation** using the closed-form **Normal Equation** and pure NumPy.

---

## 📌 Project Overview

Linear Regression models the relationship between a dependent target variable ($y$) and one or more independent predictor variables ($X$):

$$y = \theta_0 + \theta_1 x_1 + \theta_2 x_2 + \dots + \theta_n x_n + \epsilon$$

In matrix notation:
$$y = X\theta + \epsilon$$

This repository compares:
1. **Scikit-Learn Baseline:** Standard `LinearRegression` implementation.
2. **From-Scratch Implementation:** Parameter estimation using the closed-form Normal Equation:
   $$\theta = (X^T X)^{-1} X^T y$$

---

## 🗂️ Project Structure

```text
├── multiple_linear_regression.ipynb   # Complete interactive Jupyter Notebook
├── README.md                          # Project documentation
└── requirements.txt                   # Required Python packages
