# Data Cleaning & Visualization Project

## Overview
This project cleans and analyzes an employee dataset containing **43 rows and 5 columns**.

## Dataset fields
- Name
- Age
- Salary
- Join_Date
- Department

## Data quality checks
- Missing Age values: **4**
- Missing Salary values: **7**
- Exact duplicate rows: **1**

## Cleaning approach
1. Convert `Join_Date` to datetime.
2. Fill missing `Age` values with the median age (**36**).
3. Fill missing `Salary` values with the median salary (**71,841**).
4. Remove exact duplicate rows.
5. Detect salary outliers using the IQR rule.
6. Keep original salary values and create `Salary_Cleaned` using capping for analysis.
7. Extract joining year and month.

## Visualizations
- Age distribution
- Employees by department
- Average cleaned salary by department
- Salary outlier analysis
- Employees joining by year

## Files
- `Data_Cleaning_Visualization.ipynb` — complete notebook
- `sample_data_cleaning_project.xlsx` — raw dataset
- `raw_dataset.csv` — raw CSV copy
- `cleaned_dataset.csv` — cleaned dataset
- `cleaned_dataset.xlsx` — cleaned Excel file
- `visualizations/` — exported charts
- `requirements.txt` — Python dependencies

## How to run
Open the notebook in Jupyter Notebook, JupyterLab, Google Colab, or VS Code and run the cells from top to bottom.
