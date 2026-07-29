# 📈 Sales Prediction using Python

Predicting sales from advertising spend using regression analysis —  Data Science internship.

## 🎯 Problem Statement
Can we predict `Sales` from advertising spend, and which media channel (TV, Radio, Newspaper) drives it most? This project builds a Simple Linear Regression model to answer that question using the classic **Advertising dataset** (ISLR).

## 🔍 Approach
1. **EDA** — inspected distributions, checked for outliers and nulls, and used pairplots/heatmaps to identify which channel correlates most strongly with Sales.
2. **Model Building** — fit an Ordinary Least Squares (OLS) regression of `Sales` on `TV` spend using `statsmodels`, after a 70/30 train-test split; then rebuilt the same model with `scikit-learn`'s `LinearRegression` to cross-validate the results with a standard ML workflow.
3. **Model Evaluation** — validated regression assumptions via residual analysis (normality, homoscedasticity) and evaluated out-of-sample performance using RMSE and R².
4. **Prediction** — used the trained model to predict sales for a new, hypothetical advertising budget.

## 📊 Key Results
| Metric | Value |
|---|---|
| Model | Sales = 6.948 + 0.054 × TV |
| R² (Train) | 0.816 |
| R² (Test) | ~0.79 |
| Key driver | TV advertising spend |

**Takeaway:** TV advertising spend explains ~82% of the variance in sales, and every additional $1,000 spent on TV ads is associated with ~54 additional units sold.

## 🛠 Tools & Libraries
Python · Pandas · NumPy · Matplotlib · Seaborn · Statsmodels (OLS) · Scikit-learn (LinearRegression)

## 📁 Files
- `sales-prediction-simple-linear-regression.ipynb` — full analysis notebook (code, charts, and commentary)
- `advertising.csv` — dataset
- `sales-prediction-report.html` — rendered, shareable HTML version of the notebook

## 🚀 Next Steps
Extend to a **multiple linear regression** using TV + Radio to see if predictive accuracy improves further.

---
*Data Science Internship Project*
*@2026 All Rights Reserved SUBHARAJ NANDI*

About Author:
Subharaj Nandi
B.Tech CSE (AI & ML)
Sanskriti University



