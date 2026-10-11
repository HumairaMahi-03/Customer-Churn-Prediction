# Customer Churn Prediction

## Project Overview
This project analyzes customer churn in a telecommunications company and aims to develop a machine learning model to identify customers who are at risk of leaving.

## Dataset
- Total customers: 7,043
- Total columns: 21
- Target variable: `Churn`
- Customers who churned: 26.54%
- Customers who stayed: 73.46%

## Exploratory Data Analysis (EDA)

### Key Findings
1. **Contract Type:** Month-to-month customers have a churn rate of 42.71%, compared with 11.27% for one-year contracts and 2.83% for two-year contracts.
2. **Customer Tenure:** Customers with 0–12 months of tenure have a churn rate of 47.44%, compared with 9.51% among customers with 49–72 months of tenure.
3. **Monthly Charges:** Churned customers have higher average monthly charges (74.44) than retained customers (61.27).

### Business Insights
- Investigate retention strategies for month-to-month customers.
- Focus on improving the experience of newly acquired customers.
- Examine pricing and service-related factors among customers with higher monthly charges.

These findings describe associations and do not establish causation.

## Project Status
Currently completing exploratory data analysis. Data preprocessing, feature engineering, model training, and evaluation are planned next.

## Tools and Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.