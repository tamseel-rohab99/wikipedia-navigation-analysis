# Wikipedia User Navigation Analysis

Real-time analysis of Wikipedia user navigation patterns using Apache Spark, Delta Lake & Databricks. Medallion Architecture (Bronze→Silver→Gold) pipeline processing 620M+ rows of clickstream & pageview data (2022-2025), visualized via Power BI dashboard.

## Dashboard
![Dashboard](images/dashboard.png)

## Project Overview
This project builds a complete Big Data pipeline to analyze how users navigate Wikipedia articles over 4 years (2022-2025).

## Tech Stack
- Apache Spark (PySpark)
- Databricks Free Edition
- Delta Lake
- Power BI (DirectQuery)
- Python 3

## Architecture
Bronze (Raw Data) → Silver (Cleaned) → Gold (Aggregated Dashboard Table)

## Key Findings
- 148.3M total page views across 2022-2025
- Peak traffic hour: 21:00 UTC
- Top article: Artificial Intelligence (7.3M views)
- 66% navigation via Internal Links
- 6.2M unique articles observed

 Dataset
- Wikipedia Clickstream Data (540M rows)
- Wikipedia Pageview Data (80M rows)
- Source: Wikimedia Dumps 2022-2025

