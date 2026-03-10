# Asset Pricing Analysis: Martingale vs. Fundamental (CAPM & Fama-French)

## 📌 Project Overview
This repository contains the empirical analysis for an asset pricing study. The primary objective is to test the debate between the Martingale (efficient market) hypothesis and the Fundamental (multi-factor) approach to asset pricing. 

Specifically, this project compares the predictive power and risk-adjusted performance of the **Capital Asset Pricing Model (CAPM)** against the **Fama-French 3-Factor (FF3F) model** for a portfolio of major U.S. Technology stocks (Apple, Microsoft, Alphabet, Nvidia, Meta) from 2015 to 2024.

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3
* **Data Manipulation:** `pandas`, `numpy`
* **Financial Data Extraction:** `yfinance`
* **Statistical Modeling:** `statsmodels` (OLS Regression, Rolling OLS)
* **Data Visualization:** `matplotlib`

## 📂 Files in this Repository
* `asset_pricing_analysis.ipynb`: The main Jupyter Notebook containing all data extraction, statistical modeling, analysis, tables, and visualizations. *(Note: Renamed from AP project.ipynb for formatting best practices)*
* `F-F_Research_Data_Factors.csv`: The Fama-French 3-Factor historical dataset used to calculate the size (SMB) and value (HML) premiums.
* `README.md`: Project documentation and summary of findings.

## 🚀 How to Run the Analysis
1. Clone this repository to your local machine.
2. Ensure you have the required Python libraries installed (`pip install pandas numpy yfinance statsmodels matplotlib`).
3. Make sure the `F-F_Research_Data_Factors.csv` file is located in the same directory as the Jupyter Notebook.
4. Run the notebook sequentially. The script will automatically pull the latest historical stock data via the Yahoo Finance API before executing the regression models.

## 📊 Key Findings & Conclusion
*(Note: Replace the bracketed text with your actual findings from the notebook!)*

* **CAPM vs. FF3F Performance:** The Fama-French 3-Factor model yielded a higher R-squared value of **[Insert %]** compared to CAPM's **[Insert %]**, indicating that the multi-factor model better explains the variance in the tech portfolio's returns.
* **Alpha Generation:** After controlling for market risk, size, and value factors, the portfolio generated a statistically significant alpha of **[Insert Number]**, suggesting [explain what this implies about the efficient market hypothesis for these specific stocks].
* **Factor Sensitivity:** The regression analysis revealed a high sensitivity to the **[Market / SMB / HML]** factor (Coefficient: **[Insert Number]**), which aligns with the growth-oriented nature of the selected technology equities.
