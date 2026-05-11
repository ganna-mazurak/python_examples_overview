## Project Overview
This project focuses on analyzing a multi-year global sales dataset from a retail company operating across both physical and online channels. The primary objective was to transform raw, fragmented data into a clean, unified dataset to uncover trends in profitability, shipping efficiency, and regional performance.

## Tech Stack
- Language: Python
- Libraries: Pandas, NumPy (Data Manipulation), Matplotlib, Seaborn (Visualization)
- Platform: Google Colab

## Project Workflow
1. Data Integration & Cleaning
   - Schema Mapping: Consolidated three distinct datasets (events, products, and countries) using primary/foreign key relationships.
   - Data Integrity:
     - Identified and handled missing values with documented justifications.
     - Resolved data type discrepancies and standardized date formats.
   - Advanced Deduplication: Cleaned "hidden" duplicates caused by whitespace, case sensitivity (Upper/Lower), and Cyrillic/Latin character similarities.
   - Anomaly Detection: Investigated and resolved outliers to ensure statistical accuracy.

2. Exploratory Data Analysis (EDA)
   - Core Metrics: Calculated high-level KPIs, including total order volume, gross profit, and global market reach.
   - Sales Performance:
     - Segmented Revenue and Profit by Product Category, Geography, and Sales Channel (Online vs. Offline).
     - Identified top-performing markets and product "heroes."
   - Logistics Analysis:
     - Measured the time interval between order placement and shipping.
     - Correlated shipping speeds with profitability to identify operational bottlenecks.
   - Trend & Seasonality:
     - Analyzed sales dynamics over time to pinpoint growth trends.
     - Used day_name() analysis to identify day-of-week patterns and seasonal product fluctuations.

## Key Business Insights
- Channel Efficiency: Comparison of profit margins between online and offline stores.
- Regional Hotspots: Visualization of regions with the highest growth potential versus those with high shipping delays.
- Operational Impact: Insights into how shipping lag affects the bottom line.