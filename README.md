# Walmart Data Analysis Project

## Project Overview
This project focuses on **data cleaning, exploration, and SQL-based analysis** of Walmart's sales data. The dataset was processed in Python using **VS Code** and later transferred to **pgAdmin** for SQL queries to derive business insights.

## Dataset
The dataset consists of Walmart sales records stored in the following files:
- **Walmart.csv** - Raw dataset
- **Walmart_cleaned.csv** - Cleaned dataset after preprocessing

**Dataset Source:**
This dataset was obtained from Kaggle: [Walmart 10K Sales Dataset](https://www.kaggle.com/datasets/najir0123/walmart-10k-sales-datasets/data)

## Workflow
1. **Data Import & Cleaning** (Python, Pandas)
   - Imported `Walmart.csv` in a Jupyter Notebook (`walmart.ipynb`).
   - Handled missing values, removed duplicates, and corrected data types.
   - Exported the cleaned dataset as `Walmart_cleaned.csv`.

2. **SQL Analysis** (PostgreSQL, pgAdmin)
   - Loaded `Walmart_cleaned.csv` into PostgreSQL.
   - Wrote and executed multiple SQL queries in `walmart.sql` to solve business problems.

## Files & Description
| File Name            | Description                                      |
|----------------------|------------------------------------------------|
| `Walmart.csv`       | Raw Walmart dataset                           |
| `Walmart_cleaned.csv` | Preprocessed dataset after cleaning           |
| `walmart.ipynb`     | Jupyter Notebook with Python data processing   |
| `walmart.sql`       | SQL queries used for business analysis        |

## Key Insights & Analysis
- Performed **data cleaning & transformation** in Python.
- Used **SQL queries** to extract insights like **top-performing products, revenue trends, and customer behavior**.
- Provided **business recommendations** based on data analysis.


## Tools & Technologies Used
- **Languages:** SQL, Python
- **Databases:** PostgreSQL
- **Libraries:** Pandas, Requests, Matplotlib
- **Data Sources:** Walmart data from Kaggle, API
- **Skills:** Data cleaning, date manipulation, API integration, SQL querying, data visualization
