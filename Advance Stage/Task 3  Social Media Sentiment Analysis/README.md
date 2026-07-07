# Task 3 – Social Media Sentiment Analysis

## Overview
This project performs **social media sentiment analysis** on posts related to a brand, product, or event.  
The goal is to classify posts into **Positive, Negative, or Neutral** categories and provide actionable insights for marketing and customer engagement strategies.

---

## Dataset
- **File:** `sentimentdataset.csv`  
- **Source:** Kaggle Social Media Sentiment Analysis Dataset  
- **Columns:**
  - `Text` – Social media post content  
  - `Sentiment` – Original label (if available)  
  - `Timestamp` – Date and time of post  
  - `User`, `Platform`, `Hashtags`, `Retweets`, `Likes`, `Country`, `Year`, `Month`, `Day`, `Hour`  

- **Columns added during analysis:**
  - `clean_text` – Preprocessed and cleaned text  
  - `compound` – VADER sentiment score  
  - `predicted_sentiment` – Sentiment predicted by VADER  
  - `sentiment` – Final sentiment used for insights

---

## Environment & Libraries
- Python 3.11+  
- Required Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `wordcloud`
  - `nltk`
  - `vaderSentiment`

### Installation
```bash
pip install pandas numpy matplotlib seaborn wordcloud nltk vaderSentiment
````

---

## Steps Performed

### 1. Data Loading

* Loaded the dataset using Pandas.
* Checked columns, missing values, and duplicates.
* Removed unnecessary index columns.

### 2. Data Cleaning

* Converted all text to lowercase.
* Removed URLs, special characters, and extra spaces.
* Stored cleaned text in the `clean_text` column.

### 3. Sentiment Analysis

* Used **VADER sentiment analyzer** from NLTK.
* Calculated `compound` sentiment score.
* Classified posts:

  * Positive (compound ≥ 0.05)
  * Negative (compound ≤ -0.05)
  * Neutral (-0.05 < compound < 0.05)
* Stored predictions in `predicted_sentiment`.

### 4. Visualization

* **Bar chart** and **pie chart** for sentiment distribution.
* Word clouds for **positive** and **negative** posts.
* (Optional) Trend analysis over time using timestamp.

### 5. Insights & Reporting

* Total number of posts by sentiment.
* Top 5 positive and negative posts.
* Key takeaways for marketing and customer engagement strategies.

---

## Key Results

* **Total Posts:** 732
* **Sentiment Distribution:**

  * Positive: 462
  * Negative: 187
  * Neutral: 83
* **Insights:**

  * Majority of posts are positive → strong brand perception.
  * Negative posts indicate areas for marketing improvement.
  * Neutral posts highlight opportunities for engagement.

---

## How to Run

1. Open `analysis.ipynb` in Jupyter Notebook or VS Code.
2. Run all cells sequentially.
3. Check outputs for:

   * Cleaned text
   * Predicted sentiment
   * Visualizations (bar/pie chart, word clouds)
   * Insights
4. Export notebook as PDF if required for submission.

---

## Notes

* Ensure the `Text` column exists in the dataset before running the notebook.
* Optional columns like `User`, `Platform`, `Retweets`, `Likes`, `Country`, and timestamp columns can be skipped if trend analysis is not required.
* Notebook is designed to work with similar social media sentiment datasets with minimal modification.

---
