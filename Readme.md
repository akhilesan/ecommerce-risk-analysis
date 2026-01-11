# Ecommerce Risk Analysis 📊

## Project Overview
This project analyzes **9,994 e-commerce transactions** to identify profitability drivers and operational risks.  
The focus goes beyond revenue to examine how discounts, product structure, customer concentration, and time-based trends impact profit stability.

## Objectives
- Identify loss-making patterns in e-commerce transactions
- Quantify the impact of discounting on profitability
- Analyze product, customer, and time-based risk factors
- Provide data-driven recommendations for sustainable profit growth

## Dataset
- Source: Retail / Superstore-style transactional dataset
- Records: 9,994 transactions
- Key features: Sales, Profit, Discount, Category, Sub-Category, Customer, Order Date

## Key Quantified Insights
- **72.0%** of loss-making orders originate from high-discount transactions
- **17.6%** of sub-categories generate negative cumulative profit
- **Top 10% of customers contribute 57.3% of total profit**
- Monthly profit volatility reaches **~118%**, indicating unstable profit performance

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Project Structure

ecommerce-risk-analysis/
├── data/
├── images/
├── notebooks/
│   └── Ecommerce_Risk_Analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore


## How to Run
1. Clone the repository  
2. Install dependencies using `pip install -r requirements.txt`  
3. Open the notebook in Jupyter and run all cells sequentially  

## Key Takeaway
High sales volume does not guarantee profitability.  
Controlling discounts, addressing loss-making sub-categories, and protecting high-value customers are critical for achieving sustainable and predictable profit growth.
