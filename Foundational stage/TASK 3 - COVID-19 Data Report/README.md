# Task 3 - COVID-19 Data Analysis Report

## Objective
To analyze global COVID-19 case data to observe daily case progression, recovery trends, death counts, and visualize long-term pandemic patterns.

## Dataset
- File: covid_19_clean_complete.csv
- Source: Kaggle (Corona Virus Report Dataset)
- Contains country-wise COVID-19 data including daily confirmed, recovered, and death counts.

## Steps Performed
1. Loaded and cleaned the dataset:
   - Converted date column to proper datetime format
   - Filled missing values where needed
2. Grouped data by date to compute global totals for:
   - Confirmed cases
   - Recovered cases
   - Deaths
3. Calculated daily new confirmed cases using value difference.
4. Created visualizations:
   - Line charts for confirmed, recovered, and death trends
   - Bar chart showing daily new cases
   - Trend line indicating overall pandemic progression
5. Performed optional country-wise filtering for focused analysis.

## Insights from COVID-19 Data Analysis

### 1. Case Trends
- Confirmed cases show rapid early growth, reflecting initial global spread.
- Recovery counts increased significantly over time due to improved medical response.

### 2. Daily Case Patterns
- Daily new cases reveal multiple peaks, indicating several outbreak waves.
- A sharp rise in new infections corresponds with global pandemic phases.

### 3. Overall Progression
- Trend line shows strong upward movement in confirmed cases during the initial phases.
- The pandemic progression reflects exponential behavior early on.

### 4. Observations
- Countries show different patterns based on health infrastructure and response timing.
- Later phases show stabilization in some regions due to vaccination and control measures.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly (optional)
- Jupyter Notebook or VS Code

## Files Included
- analysis.ipynb
- covid_19_clean_complete.csv
