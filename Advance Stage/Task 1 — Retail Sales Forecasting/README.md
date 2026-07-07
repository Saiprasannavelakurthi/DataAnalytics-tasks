# Retail Sales Forecasting - Task 1

## Overview

Analyzed retail sales data to forecast future demand using time series analysis. Built ARIMA model to predict 12-week sales and provided inventory recommendations.

---

## What Was Done

1. Loaded and cleaned 3 CSV files (sales, features, stores)
2. Analyzed seasonality: Q4 peak (28,627 dollars), Q3 low (16,800 dollars)
3. Built SARIMAX(1,1,1) time series model
4. Test accuracy: RMSE=7,474.89, MAE=6,642.22, MAPE=37.75%
5. Forecasted next 12 weeks: 22,528 - 25,186 dollars
6. Provided inventory recommendations by period

---

## Key Results

Peak Period (November)
- Expected sales: 25,186 dollars
- Action: Increase inventory 30-50%
- Stock level: 34,000 dollars
- Order frequency: Daily

Average Period
- Expected sales: 23,500 dollars
- Action: Maintain standard
- Stock level: 32,000 dollars
- Order frequency: 2-3 times per week

Low Period (December)
- Expected sales: 22,528 dollars
- Action: Reduce inventory 20-30%
- Stock level: 28,000 dollars
- Order frequency: Once weekly

---

## Files in Repository

- analysis.ipynb - Complete analysis with 14 cells
- README.md - Full documentation
- requirements.txt - Python dependencies
- data/ folder - 3 CSV files from Kaggle

---

## How to Run

```
pip install -r requirements.txt
jupyter notebook analysis.ipynb
```

---

## Dataset

Source: Kaggle Retail Data Analytics
Records: 421,570 observations
Period: Feb 2010 - Oct 2012 (143 weeks)
Stores: 45 retail locations

---


