
# CodeAlpha_EDA — Online Retail Sales Analysis

## Project Overview
Exploratory Data Analysis (EDA) of an online retail transaction dataset using Python. This project analyzes revenue trends, top-selling products, country-wise sales, and daily revenue distribution.

## Internship
Developed as part of the CodeAlpha Data Analytics Internship.

## Objectives
- Inspect and clean retail transaction data.
- Analyze missing values and duplicate records.
- Calculate revenue using Quantity × UnitPrice.
- Identify top products and countries by revenue.
- Explore monthly sales trends and daily revenue distribution.

## Dataset
**Source:** UCI Machine Learning Repository — Online Retail

https://archive.ics.uci.edu/dataset/352/online+retail

The original dataset contains 541,909 transactions and eight columns.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Google Colab and Jupyter Notebook

## Visualizations
1. Monthly Retail Revenue
2. Top 10 Products by Revenue
3. Top 10 Countries by Revenue
4. Distribution of Daily Retail Revenue

## Key Findings
- Original dataset: 541,909 records.
- Cleaned dataset: 524,878 records.
- Total revenue reported by the analysis: approximately £10,642,110.80.
- Unique invoices: 19,960.
- Unique product codes: 3,922.
- Countries represented: 38.
- The United Kingdom generated the highest country-level revenue.

These figures depend on the cleaning and filtering rules used in the notebook. Revenue is not the same as profit.

## How to Run
1. Download or open `01_retail_eda.ipynb` in Google Colab.
2. Download the dataset from the UCI source above.
3. Upload `Online Retail.xlsx` when prompted by the notebook.
4. Run the notebook cells in order to reproduce the analysis.

Install the required libraries if necessary:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

## Project Files
- `01_retail_eda.ipynb` — analysis code and visualizations
- `README.md` — project documentation

## Acknowledgements
Dataset provided by the UCI Machine Learning Repository for educational and analytical use.

