# Mutual Fund Analytics Platform

## Project Overview

This project analyzes mutual fund schemes, NAV performance, fund house trends, SIP inflows, portfolio holdings, and benchmark indices using Python, Pandas, SQL, and data visualization tools.

## Project Structure

```text
data/
├── raw/
├── processed/

notebooks/
sql/
dashboard/
reports/
```

## Day 1 Progress - Data Ingestion & Exploration

### Tasks Completed

* Created project folder structure.
* Initialized Git repository and pushed to GitHub.
* Installed required Python libraries.
* Created Jupyter Notebook environment.
* Loaded and explored the fund_master dataset.

### Dataset Summary

* Dataset: 01_fund_master.csv
* Rows: 40
* Columns: 15
* Missing Values: 0
* Duplicate Records: 0

### Key Findings

* 10 fund houses represented.
* SBI Mutual Fund, HDFC Mutual Fund, ICICI Prudential MF, and Nippon India MF have the highest number of schemes.
* Equity funds: 34
* Debt funds: 6
* Most common risk category: Moderate

### Data Quality Observations

* No missing values found.
* No duplicate records found.
* AMFI Code appears to be the primary key.
* launch_date should be converted to datetime format for analysis.

### Next Steps

* Explore NAV history dataset.
* Validate AMFI codes across datasets.
* Perform risk-return analysis.
* Build fund performance dashboard.
