# 🛢️ Oil & Natural Gas Analytics and Visualization Platform

An end-to-end data analytics project focused on ingesting, cleaning, restructuring, and visualizing historical and trend data for crude oil and natural gas markets. This repository combines Python Jupyter Notebooks for data preparation and feature engineering with an interactive Power BI report for market intelligence and visual storytelling.

---

## 📌 Project Overview

Energy commodities like oil and natural gas exhibit dynamic price, supply, and demand fluctuations. This project provides:
- Automated workflows to clean and restructure messy commodity datasets.
- Exploratory Data Analysis (EDA) on key production, consumption, and price metrics.
- A comprehensive Power BI report dashboard for interactive exploration and stakeholder reporting.

---

## 🗂️ Repository Structure

```plaintext
├── OIL_DATA.ipynb              # Extraction, preprocessing, and EDA for crude oil datasets
├── NATURALGAS_DATA.ipynb       # Extraction, preprocessing, and EDA for natural gas metrics
├── Column_reforming.ipynb      # Data transformation, reshaping, and schema standardization
├── Oil_and_Gas_Analytics.pbix  # Power BI report file containing data models and dashboard views
└── README.md                   # Project documentation
⚙️ Key Components
1. Data Cleaning & Transformation (Jupyter Notebooks)
OIL_DATA.ipynb: Loads raw crude oil records, handles missing/anomalous values, calculates rolling averages, and inspects seasonal volatility.

NATURALGAS_DATA.ipynb: Processes natural gas supply, consumption, and storage numbers, preparing standardized metrics for cross-commodity comparisons.

Column_reforming.ipynb: Standardizes schemas, converts date/time types, pivots/unpivots columns for normalized analytical modeling, and outputs clean tabular data.

2. Interactive Power BI Dashboard
Star/Snowflake Data Model: Relates cleaned time-series data tables with common date and regional dimensions.

Custom DAX Measures: Computes Year-over-Year (YoY) growth, running totals, price spread indicators, and volumetric trends.

Dynamic Filters & Slicers: Allows slicing by commodity type, time horizon, region, and reporting intervals.

🚀 Getting Started
Prerequisites
Python 3.8+

Power BI Desktop (to view and interact with the .pbix report)

Python Dependencies
Install the required Python packages:

Bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
Running the Analysis
Clone the Repository:

Bash
git clone [https://github.com/your-username/oil-natural-gas-analytics.git](https://github.com/your-username/oil-natural-gas-analytics.git)
cd oil-natural-gas-analytics
Run Notebooks:
Launch Jupyter Notebook or JupyterLab:

Bash
jupyter notebook
Open and execute Column_reforming.ipynb, OIL_DATA.ipynb, and NATURALGAS_DATA.ipynb in sequence.

Open the Dashboard:

Open the .pbix file in Power BI Desktop.

Refresh data sources if linked to local transformed CSV/Excel exports.

📈 Key Insights & Features
Market Trends: Analyze long-term price cycles and seasonal swings across oil and gas assets.

Reformed Schema: Modular scripts allow quick integration of newly released historical datasets.

Executive Visualization: Power BI dashboard designed for immediate scannability and performance tracking.
