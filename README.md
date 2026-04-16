# Home Sales Spark Analysis

## Overview
A PySpark SQL analysis of home sales data, exploring average pricing trends 
across bedroom count, bathroom count, square footage, floors, and view ratings. 
Demonstrates Spark performance optimization through caching and parquet partitioning.

---

## Key Analysis
- Average price of four-bedroom homes sold per year
- Average price of three-bedroom, three-bathroom homes by year built
- Average price of homes with three beds, three baths, two floors, 
  and 2,000+ sq ft by year built
- Average price per view rating for homes priced at $350,000 or above, 
  with runtime comparison across uncached, cached, and parquet queries

---

## Concepts Demonstrated
- SparkSQL temporary views
- Query runtime benchmarking
- Table caching and uncaching
- Parquet file partitioning by `date_built`

---

## Tech Stack
- Python
- Apache Spark (PySpark)
- SparkSQL
- Jupyter Notebook / Google Colab

---

## Repository Contents
| File | Description |
|------|-------------|
| `Home_Sales.ipynb` | Full analysis notebook |
| `home_sales_revised.csv` | Source dataset |

---

## Data Source
Provided home sales dataset containing price, bedrooms, bathrooms, 
floors, square footage, view rating, and date built fields.
