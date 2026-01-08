# oura-ring-analytics
End-to-end analytics project using wearable health data to analyze recovery, sleep quality, and fatigue trends.

# Oura Ring Analytics Project

## Overview
This project analyzes raw wearable health data from an Oura Ring to evaluate recovery, sleep quality, and fatigue trends over time. The goal is to transform complex daily biometric data into clear, interpretable monthly insights that support training balance and recovery awareness.

## Tools & Technologies
- Python (pandas)
- Excel
- Power BI
- GitHub

## Data Processing
- Parsed semicolon-delimited CSV files
- Extracted nested JSON contributor metrics
- Cleaned and standardized daily readiness and sleep data
- Aggregated daily records into monthly performance summaries

## Key Metrics
- Readiness score trends
- Sleep quality and variability
- HRV-based recovery indicators
- Monthly recovery index
- Fatigue risk flags

## Dashboard
A Power BI dashboard visualizes monthly recovery trends, sleep quality, HRV patterns, and fatigue risk indicators to support data-driven insights.

## Project Structure
- `scripts/`: Python data cleaning and aggregation scripts
- `data/`: Cleaned and aggregated datasets
- `dashboard/`: Power BI dashboard file

## Future Enhancements
- Incorporate activity and training load metrics
- Add predictive fatigue modeling
- Expand time-series analysis

