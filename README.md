# 🧩 Automated Data Quality Assessment & Monitoring System

## Overview
This project builds an **end-to-end data quality assessment pipeline** that cleans, profiles, visualizes, and monitors dataset health using Python.

## Features
- Data cleaning and standardization  
- EDA-based profiling  
- Data Quality Metric computation  
- Dashboard visualization  
- Automated monitoring simulation  

## Tech Stack
- **Language:** Python  
- **Libraries:** pandas, numpy, plotly, dash  
- **Environment:** Jupyter Notebook  

## Structure
| Notebook/File | Description |
|----------------|-------------|
| `01_data_cleaning_and_profiling.ipynb` | Cleaning, transformation and Profiling |
| `02_data_quality_dashboard.ipynb` | Visualization |
| `03_data_quality_monitoring.ipynb` | Automated monitoring |
| `data_profile.csv` | EDA and Profile summary output |
| `data_quality_log.csv` | Monitoring results |
| `data_cleaning_log.csv` | Cleaning results |
| `news_events_cleaned.csv` | Cleaned data |
| `data_quality_summary.csv` | Quality summary |

## SQL Schema (Conceptual)
```sql
CREATE TABLE data_quality_metrics (...);
CREATE TABLE data_profile (...);


Automation Notes

A Python-based monitoring script logs data quality metrics over time and generates alerts when thresholds are breached.

How to Run

Open Jupyter Notebook

Run each notebook sequentially:

01_data_cleaning_and_profiling.ipynb → 02_data_quality_dashboard.ipynb → 03_data_quality_monitoring.ipynb

Review output CSVs and charts.

