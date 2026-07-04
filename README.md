# 🛒 E-Commerce Sales & Customer Behavior Analysis

![Python](https://img.shields.io/badge/Python-3.11%2B-blue)
![Pandas](https://img.shields.io/badge/pandas-data--analysis-blue)

This project analyzes e-commerce sales data to understand revenue patterns, regional
sales distribution, and how customer spending varies by age. The goal is to find
insights that could inform business decisions around product focus, regional
strategy, and target demographics.

## 📁 Files in this repo

| File | What it is |
| :--- | :--- |
| `ecommerce_sales_data.csv` | Raw sales data (user IDs, products, prices, dates) |
| `EDA_Sales_Performance.ipynb` | Data cleaning and exploratory analysis |
| `Executive_Insights_Summary.pdf` | Summary of findings |

## 🛠️ What I did

**1. Data cleaning**
- Removed duplicate records
- Standardized category names and price formats
- Checked and handled missing values

**2. Analysis & visualization**
- Built revenue breakdown charts by product category
- Mapped regional sales distribution
- Plotted customer age vs spending to look for patterns

## 💡 Key insights

**1. Electronics leads revenue**
Electronics is the top-selling category, making up about 48% of total platform
revenue — the biggest single contributor by a wide margin.

**2. Regional sales are fairly even**
Sales are distributed fairly evenly across regions, without one region dominating —
worth digging further into whether this is due to marketing spend, population, or
other factors.

**3. Age affects spending**
The highest-value single purchases ($25,000–$35,000 range) cluster among younger
to middle-aged adults. Overall spending also tends to decline as customer age
increases past mid-career.

## 🎯 Suggested takeaways

- Since Electronics drives nearly half of revenue, it may be worth prioritizing
  inventory and marketing spend there
- Since regional sales are balanced, there may be an opportunity to identify what's
  working in top regions and apply it elsewhere
- Younger to middle-aged customers appear to be the most valuable segment — worth
  targeting them more directly in campaigns

## ▶️ How to run

```bash
pip install pandas numpy matplotlib seaborn
```

Then open `EDA_Sales_Performance.ipynb` and run all cells 🚀


