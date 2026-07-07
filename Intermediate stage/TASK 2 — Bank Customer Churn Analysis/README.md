## Task 2 – Bank Customer Churn Analysis
## Objective

To analyze the bank customer churn dataset and identify key factors that influence why customers leave the bank. The goal is to study customer demographics, financial attributes, and activity patterns to understand churn behavior.

## Dataset

File: Churn.csv

Source: Kaggle
https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers


## Steps Performed

1. Loaded the dataset using Pandas.
2. Performed data cleaning:
    - Checked for missing values
    - Removed duplicates
    - Dropped non-essential identifier columns (if present)

3. Converted categorical fields such as Gender and Geography into usable formats.
4. Conducted Exploratory Data Analysis (EDA):
    - Examined Age distribution
    - Analyzed Balance values
    - Studied customer activity (IsActiveMember)
    - Compared Tenure and CreditScore across churn categories

5. Conducted correlation analysis on numeric attributes to observe relationships.

6. Visualized findings using bar charts, boxplots, countplots, and heatmaps.

7. Summarized insights based on churn and non-churn customer patterns.

## Insights from Churn Analysis
1. Overall Churn Summary

- A significant portion of customers exited compared to those who remained.
- Churn is not evenly distributed across demographic and financial attributes.

2. Demographic Insights

- Older customers show a higher churn rate compared to younger customers.
- Geography plays a strong role in churn; certain regions show consistently higher churn levels.

Gender shows slight differences, but not a major driver of churn.

3. Financial Insights

- Customers with higher account balances have a higher tendency to churn.
- Credit score has a moderate relationship with churn; lower scores show slightly higher churn.
- Customers with only one bank product tend to churn more often.

4. Activity-Based Insights

- Inactive customers (IsActiveMember = 0) churn at a higher rate.
- Tenure does not show strong influence alone, but may combine with other features.

5. Key Drivers of Churn

- Geography
- Customer activity
- Balance
- Age
- Number of products

# Business Recommendations

- Improve customer retention strategies in regions with high churn.

- Offer personalized support and engagement programs for inactive or high-balance customers.

- Encourage customers to adopt more products to increase long-term retention.

- Monitor high-risk age groups and provide targeted services.

- Analyze customer behavior patterns regularly to update churn prevention efforts.

# Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook or VS Code

# Files Included

- analysis.ipynb
- Churn.csv

