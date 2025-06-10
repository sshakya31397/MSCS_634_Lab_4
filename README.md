# MSCS 634 - Lab 4: Regression and Regularization

### Author: Sauhard Shakya 
### Course: MSCS 634  
### Assignment: Lab 4 - Exploring Regression Techniques with Regularization  
### Dataset: Diabetes Dataset (`sklearn.datasets.load_diabetes`)

---

## Overview

This lab focuses on applying and comparing various regression techniques to model and predict diabetes progression based on patient health metrics. We implemented:

- **Simple Linear Regression**
- **Multiple Linear Regression**
- **Polynomial Regression**
- **Ridge Regression**
- **Lasso Regression**

We also evaluated these models using standard performance metrics:  
- **Mean Absolute Error (MAE)**  
- **Mean Squared Error (MSE)**  
- **Root Mean Squared Error (RMSE)**  
- **R-squared (R²)**

Visualizations were used to interpret performance, compare predicted vs. actual values, and observe the effects of model complexity and regularization.

---

## Key Insights

- **Simple Linear Regression** underfits the data because a single feature cannot explain disease progression effectively.
- **Multiple Linear Regression** improves performance by leveraging all available features, resulting in better predictions.
- **Polynomial Regression** captures non-linear relationships but risks **overfitting** as the degree increases.
- **Ridge Regression** adds L2 regularization, reducing the effect of less important features and improving generalization.
- **Lasso Regression** adds L1 regularization, effectively zeroing out weak predictors, which can simplify the model and act as automatic feature selection.
- Regularization techniques help combat overfitting, especially with complex models or small datasets.

---

## Model Performance Summary

| Model Type              | MAE   | MSE   | RMSE  | R²     |
|------------------------|-------|-------|--------|--------|
| Linear Regression      | ...   | ...   | ...    | ...    |
| Multiple Regression    | ...   | ...   | ...    | ...    |
| Polynomial (Degree=2)  | ...   | ...   | ...    | ...    |
| Ridge Regression       | ...   | ...   | ...    | ...    |
| Lasso Regression       | ...   | ...   | ...    | ...    |

*Note: Fill in your actual values above.*

---

## Challenges Faced

- **Choosing the optimal polynomial degree**: Too low leads to underfitting; too high causes overfitting.
- **Understanding regularization parameters (alpha)**: Small alpha values can under-regularize; large values may over-constrain the model.
- **Interpreting Lasso vs Ridge effects**: It was important to understand how each regularization affects feature coefficients and model sparsity.
- **Visualizing overfitting**: Required careful observation of training vs. test performance.

---

## Files Included

- `Diabetes_Regression_Analysis.ipynb` — Main Jupyter Notebook with all code, results, and graphs.
- `README.md` — This file.
- (Optional) `Walmart_Sales.csv` or other datasets used for comparison/testing.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/MSCS_634_Lab_4.git
   cd MSCS_634_Lab_4
