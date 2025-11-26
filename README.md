Data source: https://uk.investing.com/rates-bonds/uk-1-month-bond-yield-historical-data

Fixed-Income Analysis (September 2025)

Analysis of global government-bond yield data and fixed-income trends using Python and Jupyter Notebook.

📄 Project Purpose

This project analyses historical yield data for multiple countries (e.g. UK, US, Japan, China) and fixed-income securities to explore interest rate trends, yield-curve behavior, and perform basic fixed-income market evaluation. The analyses illustrate cash-flow discounting, bond-valuation logic, and yield-curve comparisons across markets — helping users understand fixed-income risks and returns.

📂 Repository Contents
File / Dataset	Content / Purpose
fixed_income.ipynb	Main Jupyter Notebook: loads yield data, computes metrics, visualises trends across fixed-income markets.
United Kingdom 10-Year Bond Yield Historical Data.csv, United States 10-Year Bond Yield Historical Data.csv, etc.	Historical yield datasets for various markets used in the analyses.
Other yield-history CSV files (e.g. Japan, China, TIPs, STIP, IEF)	Additional datasets supporting cross-market and asset-class comparison.
README.md (this file)	Overview and instructions.
🔧 What the Notebook Does / Key Features

Loads historical bond-yield data from multiple countries and instruments.

Calculates yield trends, generates yield-curve visualisations, and compares market behavior across geographies.

Implements basic fixed-income valuation logic (e.g. discounting future cash flows, bond valuation principles) for analysis and comparison. 

Provides charts and summary statistics to facilitate understanding of interest rate risk, yield differences, and fixed-income market dynamics.

Enables cross-market comparison: e.g. comparing yields in UK vs US vs Japan, highlighting differences in interest rate regimes.

🚀 How to Use / Run

Clone or download the repository.

Ensure you have Python environment with necessary libraries installed (e.g. pandas, numpy, matplotlib/seaborn).

Open and run fixed_income.ipynb in Jupyter Notebook or JupyterLab; this will load datasets and compute analyses and charts.

Optionally, replace or extend datasets if you have more recent or alternative bond-yield data, to refresh or expand analyses.

⚠️ Notes & Assumptions

The project focuses on sovereign/government bond yields — corporate bonds and credit risk analysis are not included.

Valuation is simplified using standard discount-cashflow approaches and yield-curve comparisons. More complex fixed-income features (calls, inflation adjustment, credit risk spreads, derivatives) are outside the scope.

Results depend on data quality and completeness of historical yield datasets.

🛠️ Possible Extensions

Include corporate bond data — compute yield spreads, credit-risk analysis.

Add more advanced fixed-income valuation methods (duration, convexity, interest-rate sensitivity, inflation-linked bonds).

Build interactive dashboards (e.g. using Streamlit or Dash) for exploring yield data across markets.

Automate data retrieval (e.g. via APIs) for regular updates.

Integrate fixed-income attribution: decompose total return into coupon income, roll-down yield, yield-curve changes, credit spread changes, etc. 

📌 Summary

This repository offers a straightforward, educational fixed-income analysis toolkit: combining real-world yield data, basic valuation logic, cross-market comparisons, and visual outputs in an easy-to-understand notebook. It is ideal for learning fixed-income concepts, performing market comparisons, or preparing a foundational framework for more advanced fixed-income research.

📄 References

Fixed-income analysis principles: cash-flow discounting, yield-curve valuation, risk vs. return trade-offs. 

Yield curve and return decomposition frameworks (coupon income, roll-down, credit spread shifts). 
