# Bakingo Operations — Data Analysis Project

A complete end-to-end data analysis project built as part of my data analytics portfolio.
The goal was to simulate a real-world business scenario, analyse the data, find problems,
and recommend specific fixes — the way an analyst would work inside an actual company.

---

## What This Project Is About

Bakingo is a Delhi-based online bakery that delivers cakes and desserts across major Indian
cities. This project analyses a generated operations dataset covering ~4,000+ orders from
January to December 2023.

The central question: **why is a business with high order volumes operating at a net loss?**

The analysis found 7 distinct, data-backed answers.

---

## Problems Found

| # | Problem | Key Metric |
|---|---------|------------|
| 1 | High & uncapped discount rate | Avg discount 13.3%; orders above 15% almost always at a loss |
| 2 | Overproduction & spoilage | Pastry spoilage rate ~20%; weekends worse than weekdays |
| 3 | Slow delivery driving churn | Avg delivery 65+ mins; orders over 90 mins rated below 2.8/5 |
| 4 | Low repeat customer rate | Only 33.4% return; new customer CAC is 3–4x higher |
| 5 | Workforce not matched to demand | Peak hours and weekends understaffed based on order data |
| 6 | Product mix losses at SKU level | Designer Cakes and Pastries have the highest loss rates |
| 7 | Data quality & infrastructure gaps | Inconsistent labels, missing fields, no unified database |

---

## Tools Used

- **Python 3.x** — core language
- **Pandas** — data cleaning, feature engineering, groupby aggregations
- **NumPy** — numerical operations
- **Matplotlib** — bar charts, line charts, pie charts, horizontal bar graphs
- **Seaborn** — heatmaps and statistical plots
- **Jupyter Notebook** — analysis environment

---

## Author
Aryaman Bhardwaj  
Data Analyst | Python | SQL | PySpark | Business Intelligence

