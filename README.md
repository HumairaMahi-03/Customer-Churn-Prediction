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

## Data Preprocessing

The following preprocessing steps have been completed:

- Selected 19 input features and separated the target variable (`Churn`).
- Excluded `customerID` because it is an identifier.
- Converted `TotalCharges` to a numeric data type.
- Separated numerical and categorical features.
- Split the dataset into training (80%) and testing (20%) sets.
- Verified that the training and testing sets have no missing values before preprocessing.
- Built a preprocessing pipeline using Scikit-learn's `ColumnTransformer`.
- Applied median imputation and standard scaling to numerical features.
- Applied most-frequent imputation and one-hot encoding to categorical features.
- Fitted the preprocessing pipeline on the training data and transformed the testing data without fitting on it.

### Train-Test Split and Preprocessing Results

| Item | Result |
|---|---:|
| Total records | 7,043 |
| Input features | 19 |
| Training samples | 5,634 |
| Testing samples | 1,409 |
| Processed training features | 46 |
| Processed testing features | 46 |
| Missing values in training data | 0 |
| Missing values in testing data | 0 |

The original 19 input features were transformed into 46 features after one-hot encoding and numerical preprocessing.

## Project Status

Exploratory data analysis, feature selection, train-test splitting, and preprocessing pipeline development have been completed. Model training, performance comparison, and evaluation are the next steps.
