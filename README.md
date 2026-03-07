# Insurance Policy Sales Analysis

## Overview
This project explores an anonymized insurance policy dataset using Python.

The analysis focuses on:
- policy sales trends over time,
- product-level sales performance,
- city-level sales distribution,
- payment method usage,
- and premium-based business insights.

## Key Questions
- Which products have the highest number of policy sales?
- Which cities generate the most sales?
- Which payment methods are used most frequently?
- How do policy sales change by year, month, and weekday?
- What is the total Gross Premium and total revenue including VAT?

## What’s Included
- Data cleaning and date feature engineering
- Exploratory data analysis (EDA)
- Summary tables
- Visualizations for product, city, payment method, and time-based trends
- Business insights based on premium and policy distribution

## Dataset Columns
The dataset includes fields such as:
- Date
- Product
- Gross_Premium
- Total_Incl_VAT
- City
- Payment_Status
- Payment_Method
- Policy_Start_Date
- Policy_Term
- Policy_Duration_Days
- Policy_End_Date
- Customer_ID

## Data Note
The original dataset is proprietary. This repository uses anonymized or sample data to demonstrate the analysis workflow.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook "insurance_policy_sales_analysis.ipynb"
