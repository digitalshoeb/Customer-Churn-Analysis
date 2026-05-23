# Customer-Churn-Analysis

Executive Summary – Telco Customer Churn Analysis


This analysis was conducted on the Telco Customer Churn dataset to identify the major factors influencing customer churn and to uncover patterns in customer behavior. The project included data cleaning, exploratory data analysis (EDA), and visualization using Python libraries such as Pandas, Matplotlib, and Seaborn.


Data Preparation
- Cleaned and transformed the dataset by handling missing values in the TotalCharges column.
- Converted data types appropriately for analysis.
- Checked for duplicate and null records to ensure data quality.
- Improved readability by transforming categorical values such as SeniorCitizen from numeric labels (0/1) to meaningful categories (Yes/No).

Key Findings

Overall Churn Rate
- The analysis revealed that approximately 26.5% of customers have churned, indicating a significant customer retention challenge.

Demographic Insights
- Gender showed minimal impact on churn behavior.
- Senior citizens exhibited a noticeably higher churn percentage compared to non-senior customers, suggesting that older customers may require additional support or targeted retention strategies.

Customer Tenure
- Customers with shorter tenure (especially those subscribed for only 1–2 months) were much more likely to churn.
- Long-term customers demonstrated higher retention, indicating that customer loyalty strengthens over time.

Contract Type Analysis
- Customers on month-to-month contracts had the highest churn rate.
- Customers with one-year and two-year contracts were significantly more likely to remain with the company.
- This suggests that longer-term contracts improve customer retention and reduce churn risk.

Service-Based Insights

The service-level analysis using multiple countplot subplots highlighted several important trends:
Customers who used services such as:

- Phone Service
- DSL Internet Service
- Online Security
- Device Protection
- Tech Support

were generally less likely to churn.

Higher churn rates were observed among customers who:

- lacked Online Security,
- did not use Online Backup,
- had no Tech Support,
- or had unavailable streaming-related services.

These findings suggest that bundled or value-added services contribute positively to customer retention.


Payment Method Trends
- Customers using Electronic Check as their payment method showed the highest churn behavior compared to other payment methods.
- This may indicate lower engagement, convenience issues, or a higher-risk customer segment.

Visualizations and Analysis

The project included several effective visualizations to support the analysis, including:

- Countplots for churn distribution
- Pie charts for churn percentage
- Stacked percentage bar charts
- Histograms for tenure analysis
- Multiple subplot countplots for service comparisons

These visualizations made it easier to identify patterns and communicate business insights clearly.


Business Recommendations

Based on the findings, the following strategies could help reduce churn:

- Encourage customers to move from month-to-month to long-term contracts.
- Improve onboarding and engagement for new customers during the first few months.
- Promote value-added services such as Online Security and Tech Support.
- Investigate customer experience issues related to Electronic Check payments.
- Develop targeted retention strategies for senior citizens.

Conclusion

The analysis successfully identified several key drivers of customer churn, including contract type, tenure, service usage, and payment method. The visualizations and insights generated from this project can help businesses make data-driven decisions to improve customer retention and reduce churn rates.
