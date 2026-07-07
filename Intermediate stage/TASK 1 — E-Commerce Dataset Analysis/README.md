## Task 1 - E-Commerce Dataset Analysis
## Objective

To analyze the e-commerce dataset and extract insights related to customer orders, product performance, revenue distribution, and overall business trends.

## Dataset

File: OnlineRetail.csv

Source: Kaggle (Online Retail Dataset)

Contains details such as invoice number, product description, quantity, unit price, customer ID, and country.

## Steps Performed

1. Loaded the dataset using Pandas.

2. Performed data cleaning:
    Removed missing values
    Removed cancelled orders
    Created a Revenue column

3. Calculated total revenue, average revenue, and order-level metrics.

4. Analyzed product-wise performance.

5. Analyzed country-wise sales distribution.

6. Identified top-performing and low-performing products and regions.

7. Visualized key findings using bar charts and summary tables.

## Insights from E-Commerce Data Analysis
1. Overall Sales Summary

- The dataset shows consistent sales across multiple countries and product descriptions.
- Total and average revenue values reflect stable customer purchasing behavior.
- A large difference between high and low revenue orders indicates varied order sizes and product pricing levels.

2. Product-Wise Insights

- Certain products generate significantly higher revenue compared to others.
- Frequently purchased products are mostly low-cost items but contribute large total revenue due to high quantity sold.
- Some products show low sales volume, indicating possible issues in demand, visibility, or pricing.

3. Region-Wise Insights

- The United Kingdom generates the highest total revenue because most orders originate from this region.
- Other regions such as the Netherlands, EIRE, and Germany also show strong contributions.
- Several countries show low sales, suggesting limited customer presence or low engagement.

4. Top Product Performance

- The highest revenue-generating products belong to commonly purchased household and gift items.
- These products should be prioritized for stock planning and promotional activities.
- Low-performing items may need attention regarding pricing, product relevance, or marketing.

5. Business Recommendations

- Focus on inventory optimization for top revenue-generating products.
- Improve marketing and visibility in regions with lower sales performance.
- Review low-demand products to identify factors affecting sales—such as pricing, quality, or customer preferences.
- Maintain strong engagement in the United Kingdom, as it contributes the majority of all orders.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook or VS Code

## Files Included

- analysis.ipynb
- OnlineRetail.csv
