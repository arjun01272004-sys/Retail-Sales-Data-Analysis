# Retail Sales Data Analysis

## Project Overview

This project analyzes retail store transaction data to understand sales performance, customer purchasing behavior, product category contribution, payment preferences, purchase channels, discount status, and revenue trends.

The analysis includes:

- Data loading and initial inspection
- Missing value handling
- Duplicate and data type checks
- Transaction total consistency validation
- Exploratory data analysis using visualizations
- Key business insights and recommendations

## Dataset

The dataset used in this project is `retail_store_sales.csv`.

It contains 12,575 retail transaction records with columns such as product category, item, price per unit, quantity, total spent, payment method, purchase channel, transaction date, and discount status.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

## Key Insights

- Butchers, Electric Household Essentials, and Beverages are the top revenue-generating categories.
- Higher-quantity purchases contribute the majority of total revenue.
- Online and In-Store channels generate almost balanced revenue.
- Cash is the most used payment method, while digital and card payments are also widely used.
- Quantity has the strongest relationship with Total Amount.
- Discount-related insights should be interpreted carefully because many records had unknown discount status.

## Business Recommendations

- Prioritize inventory planning for high-revenue product categories.
- Use bundle offers and quantity-based promotions to increase transaction value.
- Continue investing in both online and in-store channels.
- Support all major payment methods.
- Improve data collection for discount status to better evaluate promotional effectiveness.

## Files

- `Retail_Sales_Data_Analysis.ipynb` - Main analysis notebook
- `retail_store_sales.csv` - Retail sales dataset
- `requirements.txt` - Python libraries required to run the notebook

