# Telco Customer Churn Analysis

## Overview
This project analyzes a telecom company's customer data to identify why customers leave (churn) and predict which customers are at risk of leaving.

**Dataset:** 7,043 customers | 21 features | Source: IBM Watson / Kaggle

---

## Business Problem
Customer churn is expensive. Acquiring a new customer costs 5–7x more than keeping an existing one. This analysis helps the business identify at-risk customers before they leave so action can be taken proactively.

---

## Tools Used
- Python
- Pandas — data cleaning and manipulation
- Matplotlib & Seaborn — data visualization
- Scikit-learn — machine learning

---

## What I Did
1. Loaded and explored the dataset
2. Cleaned the data (fixed TotalCharges column, removed 11 incomplete rows)
3. Visualized churn patterns across contract type, tenure, and monthly charges
4. Built a Logistic Regression model to predict churn
5. Evaluated the model and compared with Random Forest

---

## Key Findings
- **26.5%** of customers churned
- Month-to-month customers churn at nearly **50%** — far higher than annual or two-year contracts
- New customers (low tenure) are significantly more likely to leave
- Higher monthly charges strongly correlate with churn

---

## Model Results
| Model | Accuracy |
|---|---|
| Logistic Regression | 79% |
| Random Forest | 79% |

---

## How to Run
1. Clone this repository
2. Open `Telco Customer Churn.ipynb` in Jupyter Notebook
3. Place the Excel file in the same folder
4. Run all cells in order

---

## Notes
This project started as a business analytics exercise and naturally extended into machine learning. As someone newer to ML, this was my first hands-on experience building a predictive model from scratch — from raw data cleaning all the way to model evaluation.
