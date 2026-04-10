# Telecom Customer Churn & Revenue Risk Analysis

## Project Overview

This project analyzes telecom customer churn behavior to identify high-risk customer segments, understand churn drivers, and estimate revenue at risk due to customer attrition.

Using Python, SQL, and Power BI, the project demonstrates an end-to-end analytics workflow from data cleaning and exploratory analysis to business querying and dashboard development.

---

## Business Problem

Customer churn directly impacts telecom profitability and long-term customer lifetime value.

This project aims to answer:

* Which customer segments have the highest churn risk?
* How do contract type, tenure, internet service, and payment method affect churn?
* Which segments contribute most to revenue loss?
* What actionable insights can reduce churn?

---

## Tools & Technologies Used

* **Python** – Data Cleaning, EDA, Feature Engineering
* **Pandas / NumPy / Matplotlib / Seaborn**
* **SQL (MySQL)** – Business Querying & Segmentation Analysis
* **Power BI** – Interactive Dashboard & KPI Visualization

---

## Project Workflow

1. Cleaned messy telecom customer dataset in Python
2. Performed exploratory data analysis (EDA) to identify churn patterns
3. Created SQL queries for business-focused churn analysis
4. Built Power BI dashboard for stakeholder reporting
5. Generated business insights and revenue-risk segmentation

---

## Dashboard Preview

<img width="1328" height="745" alt="dashboard_screenshotpng" src="https://github.com/user-attachments/assets/03bececa-0366-4fdd-97cf-8cfc0ee9abca" />

---

## Key Dashboard Metrics

* **Customer Base:** 5K
* **Overall Churn Rate:** 30.52%
* **Monthly Revenue at Risk:** 110.33K
* **Annual Revenue at Risk:** 1.32M

---

## Key Insights

* Month-to-month contract customers have the highest churn rate
* Early-tenure customers (0–12 months) are most likely to churn
* Fiber optic customers show significantly higher churn than other internet service types
* Electronic check users exhibit elevated churn risk
* Month-to-month contracts contribute the largest share of revenue at risk

---

## Repository Structure

```text
telecom-churn-analysis-dashboard/
│
├── data/
│   ├── raw_telecom_data.csv
│   └── cleaned_telecom_data.csv
│
├── notebooks/
│   └── telecom_churn_analysis.ipynb
│
├── sql/
│   └── telecom_churn_queries.sql
│
├── dashboard/
│   ├── telecom_churn_dashboard.pbix
│   └── dashboard_screenshot.png
│
└── README.md
```

---

## Business Recommendations

* Introduce retention campaigns for early-tenure customers
* Incentivize migration from month-to-month to long-term contracts
* Review pricing/value proposition for fiber optic customers
* Investigate churn drivers among electronic check users
* Prioritize retention strategies for high-revenue at-risk segments

---

## Author

**Priyanka Mandula**

If you found this project interesting, feel free to connect with me on LinkedIn or explore my other repositories.
