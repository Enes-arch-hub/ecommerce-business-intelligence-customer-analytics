# E-Commerce Business Intelligence & Customer Analytics

## Project Overview

This is an end-to-end data analytics and business intelligence project using the Brazilian E-Commerce Public Dataset by Olist.

The project explores e-commerce business performance through data cleaning, SQL analytics, customer behaviour analysis, product performance, and interactive Power BI dashboards.

The goal is to transform raw business data into meaningful insights that can support better business decisions.

## Project Objectives

- Analyze overall sales and revenue performance.
- Identify top-performing products and product categories.
- Understand customer purchasing behaviour.
- Evaluate payment methods and order trends.
- Investigate delivery performance and customer satisfaction.
- Build interactive business intelligence dashboards.
- Develop practical skills in Python, SQL, and Power BI.

## Technology Stack

| Tool | Purpose |
|---|---|
| Python | Data analysis and preparation |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Exploratory data analysis |
| MariaDB / MySQL | Database management and SQL analytics |
| Power BI | Interactive dashboards |
| Git & GitHub | Version control and project documentation |

## Project Structure

```text
Ecommerce_Business_Intelligence/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── 01_data_understanding.ipynb
│
├── sql/
│
├── power_bi/
│
├── documentation/
│
├── reports/
│
├── .gitignore
└── README.md
```

**Note:** Dataset files are excluded from this repository. See the Dataset Source and Attribution section.

## Project Progress

### Phase 1: Data Understanding — Completed

- Loaded and inspected eight core datasets.
- Examined dataset dimensions, data types, and missing values.
- Identified duplicate records and investigated data quality issues.
- Analyzed review scores and numerical distributions.
- Examined relationships between the datasets.
- Investigated product category translations.

### Phase 2: Data Cleaning and Preparation — Completed

- Standardized column names.
- Converted date columns into appropriate datetime formats.
- Corrected postal code formats while preserving leading zeroes.
- Validated numerical columns and investigated anomalies.
- Checked primary identifiers and dataset relationships.
- Translated product categories into English.
- Exported eight cleaned datasets.
- Verified that processed files retained their original row counts.

### Phase 3: SQL Business Analytics — Upcoming

- Import prepared datasets into MariaDB/MySQL.
- Develop analytical SQL queries.
- Analyze revenue, orders, products, and customers.
- Investigate delivery performance and customer satisfaction.

### Phase 4: Power BI Dashboards — Upcoming

Planned dashboards:

1. Executive Overview
2. Sales and Product Performance
3. Customer Behaviour
4. Delivery and Operations

## Dataset Source and Attribution

Dataset: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset is provided under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)** license.

All dataset usage and derivative materials must comply with the applicable license terms. The original and processed dataset files are not included in this repository.

## Author

**Enes Mumeita**

- GitHub: [Enes-arch-hub](https://github.com/Enes-arch-hub)
- LinkedIn: [enes_mumeita](https://www.linkedin.com/in/enes_mumeita/)

---

*This project is being developed as a practical data analytics and business intelligence portfolio project.*