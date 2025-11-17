Asset Pricing Project: Martingale vs. Fundamental

This repository contains the Python notebook and analysis for the Asset Pricing final project. The goal is to empirically test the debate between the Martingale (efficient market) hypothesis and the Fundamental (multi-factor) approach to asset pricing.

We test this by comparing the Capital Asset Pricing Model (CAPM) against the Fama-French 3-Factor (FF3F) model for a portfolio of U.S. Technology stocks from 2015 to 2024.

🗂️ Files in this Repository

AP project.ipynb: The main Jupyter Notebook containing all code, analysis, tables, and graphs.

F-F_Research_Data_Factors.CSV: The Fama-French 3-Factor data.

README.md: This file, which explains the project.

🚀 How to Run the Analysis

Step 1: Get the Fama-French Data

You must have the F-F_Research_Data_Factors.CSV file in the same folder as the notebook for the code to work.

Go to the Ken French Data Library.

Find the "Fama/French 3 Factors" link under "U.S. Research Returns Data".

Click the "CSV" link to download the file.

Unzip the file and move F-F_Research_Data_Factors.CSV into this project's root folder.

Step 2: Install Python Libraries

This script requires the following libraries. You can install them using pip:

pip install pandas
pip install yfinance
pip install statsmodels
pip install matplotlib
pip install numpy
pip install jupyter


Step 3: Run the Code

Open your terminal or command prompt.

Navigate to this project folder.

Type jupyter notebook and hit Enter.

Your web browser will open. Click on AP project.ipynb.

In the notebook, click "Cell" -> "Run All" to re-generate all the tables and graphs.
