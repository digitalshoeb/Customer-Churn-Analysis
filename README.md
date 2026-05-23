# Customer-Churn-Analysis

Project Overview

This project involves a comprehensive Exploratory Data Analysis (EDA) on a telecom customer churn dataset to identify patterns and reasons why customers are leaving the service
. By analyzing various factors such as tenure, contract types, and service usage, the goal is to provide actionable insights that can help a company improve customer retention
.

Technical Stack
- Language: Python
- Environment: Jupyter Notebook
- Libraries:

   --Pandas & NumPy: For data manipulation and numerical operations
.

  --Matplotlib & Seaborn: For data visualization and creating statistical plots
.


Data Description

The dataset, sourced from Kaggle, contains information on approximately 7,043 customers with 21 columns, including
:
- Demographics: Gender, Senior Citizen status, Partner, and Dependents
.
- Services: Phone service, Multiple lines, Internet service, Online security, Tech support, etc
.
- Account Info: Tenure, Contract type, Payment method, Monthly charges, and Total charges
.
- Target Variable: Churn (Whether the customer stayed or left)
.

Data Workflow

1. Data Cleaning & Pre-processing
- Data Inspection: Used df.info() and df.describe() to understand data types and statistical distributions
.
- Handling Nulls: Identified that TotalCharges contained blank spaces because of customers with zero tenure; these were replaced with '0' and the column was converted to a float data type
.
- Standardization: Converted SeniorCitizen values from numeric (0/1) to categorical (No/Yes) to make the analysis more readable
.
- Duplicate Check: Verified that there were no duplicate entries in the dataset based on unique Customer IDs
.

2. Exploratory Data Analysis (EDA)

A series of visualizations were created to uncover churn drivers:
- Churn Distribution: Discovered that 26.54% of the total customer base has churned
.
- Demographic Impact: Churn is not significantly gender-specific, but Senior Citizens have a much higher churn rate (approx. 41%) compared to non-seniors
.
- Tenure Trends: Most churn occurs within the first few months of service, while long-tenure customers are more likely to stay
.
- Contract Analysis: Customers on month-to-month contracts are significantly more likely to churn compared to those on one-year or two-year contracts
.
- Payment Methods: Users paying via Electronic Check show the highest tendency to churn
.

Key Insights

- Service Risks: Customers using Fiber Optic internet and those without online security or tech support services show notably higher churn rates
.
- Retention Strategy: Encouraging customers to move from month-to-month plans to longer-term contracts could drastically reduce churn
.
- Payment Optimization: Since electronic check users churn more, the company could offer incentives for switching to automated bank transfers or credit cards
.
- Initial Engagement: Focus on the first few months of the customer journey, as this is the period with the highest risk of cancellation
.
