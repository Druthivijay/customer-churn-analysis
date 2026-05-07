# Customer Churn Analysis

## Project Overview
This project analyzes customer churn behavior for a telecom company 
using the IBM Watson Telco dataset. The goal is to identify key factors 
that drive customer churn, enabling the business to take proactive 
retention strategies. Machine learning models were built to predict 
which customers are at risk of leaving, achieving 81.47% accuracy.

## What is Customer Churn?
Customer churn refers to when a customer stops doing business with 
a company. In telecom industry, churn rate is a critical KPI 
(Key Performance Indicator). A high churn rate means the company 
is losing revenue and needs to improve customer retention strategies.

## Dataset
- Source: IBM Watson Telco Customer Churn Dataset
- Size: 7,043 customers, 21 features
- Target Variable: Churn (Yes/No)

## 21 Features Explained
| Feature | Description |
|---------|-------------|
| customerID | Unique ID for each customer |
| gender | Male or Female |
| SeniorCitizen | Whether customer is senior citizen (1/0) |
| Partner | Whether customer has a partner |
| Dependents | Whether customer has dependents |
| tenure | Number of months with company |
| PhoneService | Whether customer has phone service |
| MultipleLines | Whether customer has multiple lines |
| InternetService | DSL, Fiber optic, or No |
| OnlineSecurity | Whether customer has online security |
| OnlineBackup | Whether customer has online backup |
| DeviceProtection | Whether customer has device protection |
| TechSupport | Whether customer has tech support |
| StreamingTV | Whether customer streams TV |
| StreamingMovies | Whether customer streams movies |
| Contract | Month-to-month, One year, Two year |
| PaperlessBilling | Whether customer uses paperless billing |
| PaymentMethod | Electronic check, Mailed check, etc |
| MonthlyCharges | Amount charged monthly |
| TotalCharges | Total amount charged |
| Churn | Whether customer churned (Yes/No) |

## Key Business Metrics
- **Churn Rate:** 26.54% customers left the service
- **Total Customers Analyzed:** 7,043
- **Churned Customers:** 1,869
- **Retained Customers:** 5,174

## Key Business Insights
- Month-to-month contract customers churn the most
- Customers with higher monthly charges are more likely to churn
- New customers (low tenure) have higher churn risk
- Fiber optic internet users churn more than DSL users

## Tools Used
- Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn)
- Power BI (Interactive Dashboard)
- GitHub (Version Control)

## How to Run
1. Clone the repository
2. Install requirements:
pip install pandas numpy matplotlib seaborn scikit-learn
3. Open churn_analysis.ipynb in Jupyter Notebook
4. Run all cells

## Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 81.47% |

## Dashboard
![Power BI Dashboard](power%20bi%20dashboard.png)
