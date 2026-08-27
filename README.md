# Financial Performance Dashboard

A beginner-level financial analytics project using **Python, SQL, and Tableau/Power BI**.

## What this project does

This project analyzes a fictional company's transaction data to answer basic financial questions around:

- Revenue
- Cost
- Gross profit
- Gross margin
- Monthly performance
- Product performance
- Regional performance
- Customer revenue

## Tools

- Python (Pandas)
- SQL (SQLite)
- Tableau or Power BI
- Git/GitHub

## Dataset

The dataset is **synthetic** and was created for portfolio/learning purposes. It does not contain real company or customer information.

## Project structure

```text
financial_dashboard_project/
├── data/
│   └── financial_transactions.csv
├── python/
│   └── financial_analysis.py
├── sql/
│   ├── schema.sql
│   └── analysis_queries.sql
├── tableau/
│   └── dashboard_plan.md
└── README.md
```

## How to run the Python analysis

From the `python` folder:

```bash
pip install pandas
python financial_analysis.py
```

The script calculates financial metrics and creates three files that can be imported into Tableau or Power BI.

## SQL analysis

Load `data/financial_transactions.csv` into SQLite using the table structure in `sql/schema.sql`.

Then run the queries in:

```text
sql/analysis_queries.sql
```

## Dashboard

Use the generated CSV files to build a simple financial performance dashboard in Tableau or Power BI.

The dashboard should include revenue, gross profit, margin, monthly trends, product performance, and regional performance.

## Portfolio description

> Built a financial performance dashboard using Python, SQL, and Tableau/Power BI to analyze revenue, costs, gross profit, margins, product performance, and regional trends using a synthetic transaction dataset.
