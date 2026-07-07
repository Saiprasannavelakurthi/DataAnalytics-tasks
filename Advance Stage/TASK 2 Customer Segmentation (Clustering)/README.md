
# Customer Segmentation using Clustering

**Advance Stage – Task 2 (Cognetix Technology Internship)**

## Overview

The objective of this project is to segment customers based on their demographic information, purchase behaviors, and product spending patterns. Using clustering algorithms, customers are grouped into meaningful segments that support data-driven marketing, personalization, and business planning.

The dataset used for this project is the Customer Segmentation dataset from Kaggle.

---

# Project Workflow

## 1. Data Loading and Cleaning

* Loaded the dataset using Pandas.
* Checked dataset shape, missing values, duplicates, and inconsistent values.
* Derived new features such as `Age` from `Year_Birth`.
* Ensured all necessary numerical fields were selected for clustering.

---

## 2. Feature Selection

The following attributes were used for clustering because they directly reflect customer behavior, spending habits, and engagement:

* Age
* Income
* Kidhome
* Teenhome
* Recency
* MntWines
* MntFruits
* MntMeatProducts
* MntFishProducts
* MntSweetProducts
* MntGoldProds
* NumDealsPurchases
* NumWebPurchases
* NumCatalogPurchases
* NumStorePurchases
* NumWebVisitsMonth

These features capture demographic factors, product-specific spending, and channel usage patterns.

---

## 3. Scaling

Since the variables were in different scales (for example, Income vs. Web Visits), StandardScaler was used to normalize the features before clustering.

---

## 4. Optimal Cluster Selection

Two methods were used:

### Elbow Method

The inertia curve indicated that the optimal number of clusters was around k = 5.

### Silhouette Score

Silhouette values for k = 2 to 7 were evaluated, and k = 5 provided a reasonable cluster separation.

---

## 5. Model Training

K-Means clustering with k = 5 was trained on the scaled feature set.
Cluster labels were added back to the dataframe.

---

## 6. Visualization

### PCA Visualization

Principal Component Analysis (PCA) reduced the data to two components, allowing visualization of how clusters are separated in 2D space.

### Cluster Heatmap

A heatmap of mean values for each feature across clusters was generated.
This heatmap was used to interpret and label customer segments.

---

# Final Customer Segments

Based on the cluster centers and heatmap interpretation, the following segments were identified:

### Cluster 0: High Spenders

Customers with high income and strong spending across multiple product categories, including wines, meats, and gold products. They purchase through multiple channels and contribute significantly to revenue.

### Cluster 1: Low Engagement Users

Customers with low spending, limited purchase activity, and very few store or online interactions. They represent a low-engagement group requiring reactivation strategies.

### Cluster 2: Top Value Customers

The most valuable customers with the highest income and highest spending in all major categories. They are highly active and loyal, requiring premium loyalty programs and exclusive offers.

### Cluster 3: Regular Multi-Channel Buyers

Moderate-income customers who make consistent purchases across web, catalog, and store channels. They respond well to multi-channel promotions and have balanced shopping behavior.

### Cluster 4: Budget-Conscious Customers

Older customers with moderate income but very low spending across categories. They prefer essential products and respond well to discounts and economic bundles.

---

# Key Insights

* High-value segments (Clusters 0 and 2) contribute a major portion of revenue and should be prioritized for retention and loyalty initiatives.
* Low-engagement users (Cluster 1) require targeted reactivation through email campaigns, discounts, or personalized messages.
* Multi-channel buyers (Cluster 3) are steady and reliable customers who benefit from channel-specific offers.
* Budget-conscious customers (Cluster 4) prefer low-cost purchasing and require cost-effective marketing strategies.
* Spending behaviors differ significantly across clusters, validating the use of segmentation for targeted marketing.

---

# Files Included

* Jupyter Notebook: `analysis.ipynb`
* Final segmented dataset: `customer_segmentation_final.csv`
* Cluster heatmap and PCA visualizations

---

# How to Run

1. Install required libraries:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. Open the notebook:

```
analysis.ipynb
```

3. Run all cells sequentially:

* Data preparation
* Feature scaling
* Clustering
* Visualization
* Segment labeling

4. Export the final CSV file generated at the end.

---

