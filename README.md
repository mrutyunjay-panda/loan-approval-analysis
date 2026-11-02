# Loan Approval Analysis

**Goal:** Identify what drives loan approval decisions so a lender can screen applicants faster and with less risk.

## Tools
Python (Pandas, NumPy, Matplotlib, Seaborn) | SQL (MySQL) | Power BI (DAX, KPI cards, slicers)

## Dataset
- Source: Loan Prediction Dataset (Kaggle) 
- Rows and columns: 614 rows, 13 columns


## Approach
1. **Cleaning (Python):** cleaned raw data and prepared it for analysis.
2. **Analysis (SQL):** analysed approval patterns using aggregations and window functions.
3. **Segmentation (DAX):** grouped applicants into Low, Medium and High income bands.
4. **Dashboard (Power BI):** KPI cards for Approval Rate % and Average Loan Amount, with slicers to filter by applicant profile.

## Key Insights
- Credit history is the dominant factor: **79%** of applicants with good credit were approved vs only **7.9%** without.
- Strongest segments: Semiurban areas (**76.8%**) and graduates (**70.8%**).
- Weakest segment: low-income applicants (**57.4%**).

## Dashboard
![Dashboard](screenshots/dashboard.png)

## Files
- `notebook.ipynb`: data cleaning and EDA
- `queries.sql`: SQL analysis
- `loan_dashboard.pbix`: Power BI dashboard
- `screenshots/`: dashboard images
