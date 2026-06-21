# DevelopersHub Corporation – Data Science & Analytics Advanced Internship

## Intern Submission – All 5 Tasks

**Deadline:** 30 June 2026  
**Minimum Required:** 3 of 5 tasks  
**Submitted:** All 5 tasks ✅

---

## Project Overview

| # | Task | Models / Tools | Dataset |
|---|------|----------------|---------|
| 1 | Term Deposit Subscription Prediction | Logistic Regression, Random Forest, XGBoost + SHAP | UCI Bank Marketing |
| 2 | Customer Segmentation | K-Means, PCA, t-SNE | Mall Customers |
| 3 | Energy Consumption Forecasting | ARIMA, Prophet, XGBoost | Household Power Consumption (UCI) |
| 4 | Loan Default Risk + Cost Optimization | Logistic Regression, XGBoost + Threshold Tuning | Home Credit / Credit Risk |
| 5 | Interactive Business Dashboard | Streamlit (10+ chart types) | Global Superstore |

---

## Repository Structure

```
ds_internship/
│
├── task1/
│   ├── Task1_Bank_Marketing_Classification.ipynb
│   └── README.md
│
├── task2/
│   ├── Task2_Customer_Segmentation.ipynb
│   └── README.md
│
├── task3/
│   ├── Task3_Energy_Forecasting.ipynb
│   └── README.md
│
├── task4/
│   ├── Task4_Loan_Default_Risk.ipynb
│   └── README.md
│
├── task5/
│   ├── app.py          ← Streamlit dashboard (run: streamlit run app.py)
│   └── README.md
│
└── README.md           ← This file
```

---

## How to Run Each Task

### Tasks 1–4 (Jupyter Notebooks)
```bash
# Install common requirements
pip install pandas numpy matplotlib seaborn scikit-learn xgboost shap prophet statsmodels nbformat

# Open any notebook
jupyter notebook task1/Task1_Bank_Marketing_Classification.ipynb
```
Each notebook **auto-downloads its dataset** from UCI or public mirrors — no manual download needed.

### Task 5 (Streamlit Dashboard)
```bash
pip install streamlit pandas numpy matplotlib seaborn
cd task5
streamlit run app.py
# Opens at http://localhost:8501
```
Optionally place `Global_Superstore.csv` in the task5 folder; if absent, a synthetic dataset is auto-generated.

---

## Key Skills Demonstrated

- **Data Wrangling** — missing value imputation, encoding, feature engineering
- **EDA** — distributions, correlation heatmaps, temporal patterns
- **Classification** — Logistic Regression, Random Forest, XGBoost with imbalanced data handling
- **Clustering** — K-Means, Elbow Method, Silhouette Score, PCA, t-SNE
- **Time Series** — ARIMA, Prophet seasonality decomposition, XGBoost with lag features
- **Explainability** — SHAP summary plots, waterfall plots, feature importance
- **Business Optimization** — Cost-sensitive threshold tuning, cost-benefit matrix
- **Visualisation** — 30+ charts across all tasks
- **Dashboard Development** — Streamlit with sidebar filters, KPI cards, dynamic charts

---

## Technologies Used

```
Python 3.10+
pandas, numpy
matplotlib, seaborn
scikit-learn
xgboost
shap
prophet
statsmodels
streamlit
nbformat
```

---

*All tasks completed as part of the DevelopersHub Corporation Data Science & Analytics Advanced Internship program.*
