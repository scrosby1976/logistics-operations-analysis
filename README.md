# Logistics Operations Analysis

End-to-end data analysis project using SQL and Python to evaluate driver performance, trip efficiency, and operational metrics. The project includes data preparation, analysis, and a Power BI dashboard for interactive exploration.

---

## Project Overview

This project analyzes logistics operations data to identify performance patterns across drivers, terminals, and routes. The goal is to understand workload distribution, efficiency consistency, and operational trends.

Data was extracted, cleaned, and transformed using Python (pandas) and SQL (DuckDB) in a Jupyter Notebook, then visualized in Power BI.

---

## Key Insights

- Driver efficiency is consistent across experience levels, indicating standardized processes
- Terminal performance varies in total workload, but efficiency remains tightly clustered
- Fuel usage scales predictably with distance, validating data consistency and operational stability

---

## Tools Used

- Python (pandas)
- SQL (DuckDB)
- Jupyter Notebook
- Power BI

---

## Data Source

Dataset: Logistics Operations Database (Kaggle)

---

## How to Run (Notebook)

1. Install dependencies:
   pip install kagglehub pandas duckdb

2. Open the notebook in the `/notebooks` folder

3. Run all cells:
   The dataset will download automatically using kagglehub

---

## Data & Dashboard Usage

The Power BI dashboard is built using a processed dataset located in the `/data` folder.

To view the dashboard:

1. Download the repository
2. Open the Power BI file in the `/dashboard` folder
3. If prompted, update the data source to point to the local CSV file in `/data`

The dataset was prepared using SQL and Python and represents a filtered one-year subset of the original data.

---

## Project Structure

- `/notebooks` → Data extraction, cleaning, and transformation  
- `/data` → Final dataset used for analysis and dashboard  
- `/dashboard` → Power BI dashboard file  
- `README.md` → Project overview and instructions
