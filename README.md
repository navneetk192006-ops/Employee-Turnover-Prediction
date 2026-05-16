# Employee Turnover Prediction using Logistic Regression

## Overview
This project predicts whether an employee is likely to leave the company using **Logistic Regression** models with:

- Baseline Logistic Regression
- L1 Regularization (Lasso)
- L2 Regularization (Ridge)

The project demonstrates how regularization techniques help improve model generalization and reduce overfitting.

---

## Technologies Used

- Python
- Pandas
- Scikit-learn

---

## Dataset

Dataset used: `employee_turnover.csv`

Target Column:
- `Employee_Turnover`
  - 1 → Employee Leaves
  - 0 → Employee Stays

---

## Project Workflow

1. Load Dataset
2. Split Features and Target
3. Train-Test Split
4. Train Logistic Regression Models
5. Apply:
   - L1 Regularization (Lasso)
   - L2 Regularization (Ridge)
6. Evaluate Models using:
   - Accuracy Score
   - Classification Report

---
