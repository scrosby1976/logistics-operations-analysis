## Logistics Operations Analysis

End-to-end data analysis project using SQL and Python to evaluate driver performance, trip efficiency, and operational metrics. The project includes data preparation, analysis, and a Power BI dashboard for interactive exploration.

---

## Project Overview

This project analyzes logistics operations data to identify inefficiencies in driver performance, workload distribution, and operational consistency across terminals and routes.

The goal was to move beyond basic reporting to uncover patterns in efficiency and performance that could support better resource allocation and operational decision-making.

Data was extracted, cleaned, and transformed using Python (`pandas`) and SQL (`DuckDB`) in a Jupyter Notebook, then visualized in Power BI.

---

## Key Insights

- Driver efficiency remained consistent across experience levels, suggesting performance is driven more by system design and process standardization than individual variation
- Terminal workload varied significantly, but efficiency remained tightly clustered, indicating potential opportunities to rebalance workload without impacting performance
- Fuel usage scaled predictably with distance, validating data integrity and enabling reliable performance comparisons across trips

---

## Operational Opportunities (Recommendations)

- Rebalance workload across terminals to improve capacity utilization without negatively impacting efficiency
- Investigate process or routing design as primary drivers of performance rather than focusing on individual driver optimization
- Use validated fuel and distance relationships to support benchmarking and identify outlier routes or inefficiencies

---

## Tools Used

- **Python** (`pandas`)
- **SQL** (`DuckDB`)
- **Jupyter Notebook**
- **Power BI**

---

## Data Source

- **Dataset:** Logistics Operations Database (Kaggle)

---

## How to Run (Notebook)

1. Install dependencies:

```bash
pip install kagglehub pandas duckdb
```

2. Open the notebook in the `/notebooks` folder

3. Run all cells  
   The dataset will download automatically using `kagglehub`

---

## Data & Dashboard Usage

The Power BI dashboard is built using a processed dataset located in the `/data` folder.

To view the dashboard:

1. Download the repository  
2. Open the Power BI file in the `/dashboard` folder  
3. If prompted, update the data source to point to the local CSV file in `/data`

**Note:**  
The dataset represents a filtered one-year subset prepared using SQL and Python.

---

## Project Structure

- `/notebooks` → Data extraction, cleaning, and transformation  
- `/data` → Final dataset used for analysis and dashboard  
- `/dashboard` → Power BI dashboard file  
- `README.md` → Project overview and instructions  
