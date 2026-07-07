## Task 3 – Interactive Sales Dashboard

## Objective

To design an interactive sales dashboard that visualizes and analyzes sales performance across different regions, time periods, and product categories using the Superstore dataset.


## Dataset

File: Superstore.csv

Source: Kaggle (Superstore Dataset)

Contains details such as order date, ship date, product category, sales, profit, quantity, customer segments, and geographic information.


## Steps Performed

1. Loaded the dataset using Pandas.
2. Performed data preprocessing:

   * Converted date columns (Order Date, Ship Date)
   * Created new fields such as Year and Month
   * Checked for missing values and data consistency
3. Conducted exploratory data analysis (EDA):

   * Calculated total sales, total profit, and total orders
   * Analyzed region-wise, category-wise, and product-wise performance
4. Created an interactive Power BI dashboard:

   * KPIs for Total Sales, Total Profit, Total Orders
   * Visualizations for sales trend, region-wise revenue, category-wise distribution, and top products
5. Added slicers for Year, Month, Category, Region, and Order Date range
6. Ensured all visuals respond to filters for smooth interactivity


## Insights from Sales Dashboard

1. **Overall Sales Performance**

   * Sales show a clear upward trend across the years analyzed.
   * Total sales and total profit reflect strong business performance.
   * The number of orders indicates consistent customer demand.

2. **Region-Wise Insights**

   * The West region generates the highest revenue among all regions.
   * East and Central regions also contribute significantly.
   * South shows comparatively lower sales.

3. **Category-Wise Insights**

   * Technology products contribute the most to total sales.
   * Furniture and Office Supplies also show steady performance.
   * Category distribution helps identify inventory and marketing priorities.

4. **Product-Wise Insights**

   * A few top products dominate overall revenue.
   * These items should be prioritized for stock availability and promotions.
   * Low-performing products may require review for pricing or demand issues.

5. **Business Recommendations**

   * Focus marketing efforts and stock allocation on high-performing regions and products.
   * Analyze low-sales categories to identify improvement opportunities.
   * Continue leveraging top-selling products in promotional strategies.
   * Monitor monthly and yearly trends to align inventory with demand patterns.


## Technologies Used

* Power BI
* Python
* Pandas
* Matplotlib / Seaborn
* Jupyter Notebook or VS Code


## Files Included

* analysis.ipynb
* Superstore.csv
* Superstore_Dashboard.pbix
* Superstore_Dashboard.pdf


