# Olist Customer Retention Analysis

## Objective
Understand why customer retention is low on Olist (Brazilian e-commerce) and recommend actions to improve repeat purchases.

## Dataset
Olist Brazilian E-Commerce Public Dataset (Kaggle). Only delivered orders were used.

## Tools
Python (pandas, numpy, matplotlib, seaborn), Jupyter Notebook, Power BI

## Approach
1. Merged orders, customers and payments tables
2. Calculated KPIs: repeat purchase rate, average order value
3. Built monthly cohort retention analysis
4. Created RFM customer segments
5. Built an interactive Power BI dashboard

## Key Numbers
- Total customers: 93,358
- Total revenue: 15.42M
- Average order value: 159.85
- Repeat purchase rate: about 3%

## Key Insights
- Only about 3% of customers made a repeat purchase, so most revenue comes from one-time buyers
- Monthly cohort retention stays below 1% in every cohort, so customers rarely return after the first order
- New Customers and Lost are the largest segments, while Champions and At Risk Repeat are very small

## Recommendations
- Send a follow-up offer within 30 days of the first order
- Run a win-back campaign for high-value customers who stopped buying
- Build a loyalty program for repeat customers

## Dashboard
![Dashboard](olist%20customer%20retention%20dashboard%20.png)

## Files
- `customer retenion sales.ipynb`: full analysis notebook
- `cohort_retention.csv`, `rfm_segments.csv`, `segment_summary.csv`, `monthly_trend.csv`: outputs used in Power BI
