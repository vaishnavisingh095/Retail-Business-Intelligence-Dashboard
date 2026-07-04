# Retail Business Intelligence Dashboard
### End-to-End Business Analytics & Customer Intelligence Project

> Transforming retail transaction data into actionable business insights using Python, Power BI, and customer analytics.

---

# Project Overview

Business dashboards often explain **what happened**, but decision-makers need to understand **why it happened**.

This project analyzes a retail dataset to identify the key drivers of profitability, customer behavior, regional performance, and long-term business growth.

The project combines **Python-based analytics** with an **interactive Power BI dashboard** to support data-driven business decisions.

---

# Business Problem

The company wanted to understand:

- Why is the Furniture category underperforming?
- Which customer groups generate the highest profitability?
- Why does the Central region perform worse than other regions?
- Are discount strategies improving or hurting profitability?
- Is the business actually declining over time?

---

# Project Objectives

✔ Clean and validate retail transaction data

✔ Perform exploratory data analysis (EDA)

✔ Engineer customer-level analytical features

✔ Investigate profitability drivers

✔ Analyze customer purchasing behavior

✔ Evaluate regional performance

✔ Perform customer cohort analysis

✔ Build an executive Power BI dashboard

✔ Recommend business strategies backed by data

---

# Dataset

**Dataset:** Sample Superstore

**Records:** ~9,994 Orders

**Customers:** 793

**Categories:** 3

**Regions:** 4

**Time Period:** 2014–2017

---

# Tools & Technologies

| Category | Tools |
|----------|------|
| Programming | Python |
| Data Analysis | Pandas |
| Visualization | Matplotlib |
| Dashboard | Power BI |
| Notebook | Jupyter Notebook |
| Version Control | Git & GitHub |

---

# Repository Structure

```
Retail-Business-Intelligence-Dashboard
│
├── charts/
│
├── dashboard/
│   ├── screenshots/
│   └── Superstore.pbix.pdf
│
├── data/
│   ├── Sample_Superstore.csv
│   ├── customer_summary.csv
│   └── customer_summary_final.csv
│
├── notebooks/
│   ├── 01_Data_Exploration_and_Preparation.ipynb
│   └── 02_Customer_Analytics_and_Business_Investigation.ipynb
│
├── output/
│
├── requirements.txt
│
└── README.md
```

---

# Project Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning & Validation
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
(Customer Summary Dataset)
      │
      ▼
Customer Analytics
      │
      ▼
Business Investigation
      │
      ▼
Power BI Dashboard
      │
      ▼
Business Recommendations
```

---

# Exploratory Data Analysis

The first notebook focuses on understanding the dataset before performing any business investigation.

Topics covered include:

- Data Quality Assessment
- Missing Value Analysis
- Duplicate Detection
- Outlier Investigation
- Sales Analysis
- Profit Analysis
- Regional Performance
- Segment Performance
- Category Analysis
- Sub-Category Analysis
- Customer-Level Dataset Creation

---

# Customer Analytics

The second notebook shifts from transaction-level analysis to customer-level business investigation.

Major investigations include:

### 1. Customer Profitability Analysis

Identified differences in profitability across customer purchasing behaviors.

---

### 2. Multi-Category Customer Analysis

Compared customers purchasing from one, two, and three product categories.

---

### 3. Customer Group Analysis

Grouped customers into:

- Furniture Only
- Furniture + Technology
- Furniture + Office Supplies
- All Three Categories

---

### 4. First Purchase Analysis

Investigated which product category customers purchased first.

---

### 5. Furniture Profitability Investigation

Measured how Furniture contributes to overall customer profitability.

---

### 6. Customer Churn Scenario

Estimated the potential business impact of losing different customer groups using a hypothetical churn scenario.

---

### 7. Discount Analysis

Studied the relationship between discount levels and customer profitability.

---

### 8. Regional Performance Analysis

Compared profitability and discount strategies across regions.

---

### 9. Customer Cohort Analysis

Measured customer profitability based on acquisition year while correcting for observation bias.

---

# Dashboard Pages

## Executive Overview

High-level KPIs

Business assumptions

Final conclusions

---

## Furniture Deep Dive

Customer group profitability

Furniture contribution

Customer behavior

---

## Regional Analysis

Regional profitability

Average discounts

Business recommendations

---

## Cohort Analysis

Customer acquisition cohorts

Average profitability

Business growth trends

---

# Key Business Insights

## Customer Behavior

- Multi-category customers generated substantially higher profits than single-category customers.
- Customer purchasing behavior proved to be a stronger profitability indicator than product category alone.

---

## Furniture

- Furniture was **not** the primary business problem.
- Lower profitability was concentrated among customers purchasing Furniture without additional categories.
- Tiered pricing is likely to be more effective than discontinuing the category.

---

## Regional Performance

- The Central region underperformed despite relatively high discount levels.
- Findings suggest discount strategy contributed more to weaker profitability than product mix alone.

---

## Business Growth

- Initial yearly comparisons suggested declining performance.
- After correcting for customer acquisition timing, cohort analysis indicated that newer customer cohorts generated higher average profitability.

---

# Business Recommendations

- Encourage cross-category purchasing through bundles and cross-selling.
- Introduce tiered pricing for standalone Furniture purchases while maintaining bundle discounts.
- Optimize discount strategy in the Central region.
- Prioritize retention of high-value customer groups.
- Continue monitoring cohort profitability to evaluate long-term business health.

---

# Dashboard Preview

## Executive Overview

> <img width="1148" height="654" alt="Screenshot 2026-07-04 at 3 51 37 PM" src="https://github.com/user-attachments/assets/128af99e-42f9-4f95-b940-9ed07bea6410" />

---

## Furniture Deep Dive

> <img width="1148" height="654" alt="Screenshot 2026-07-04 at 3 51 55 PM" src="https://github.com/user-attachments/assets/06af0933-547d-498b-a64d-dd8c156abd24" />

---

## Regional Analysis

> <img width="1148" height="654" alt="Screenshot 2026-07-04 at 3 52 06 PM" src="https://github.com/user-attachments/assets/c0b203af-a5d0-4a02-97f4-50981ffb535e" />

---

## Cohort Analysis

> <img width="1148" height="654" alt="Screenshot 2026-07-04 at 3 52 15 PM" src="https://github.com/user-attachments/assets/8231913f-b277-4d63-9ef1-2753f669ecb9" />

---

# Skills Demonstrated

- Business Analysis
- Customer Analytics
- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Data Visualization
- Business Intelligence
- Power BI Dashboard Development
- Python Programming
- Business Storytelling
- Analytical Thinking

---

# Future Improvements

- Customer Lifetime Value (CLV)
- Predictive Churn Modeling
- RFM Segmentation
- Price Optimization Models
- Interactive What-if Pricing Dashboard

---

# Author

**Vaishnavi Singh**

Aspiring Business Analyst | Product Analyst | Data Analyst

GitHub:
https://github.com/vaishnavisingh095

LinkedIn:
https://www.linkedin.com/in/vaishnavisingh0

---

If you found this project interesting, feel free to ⭐ the repository or connect with me on LinkedIn.
