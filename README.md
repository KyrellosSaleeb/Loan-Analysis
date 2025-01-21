# Loan Analysis Project

This project focuses on analyzing loan and customer data to assess risk, categorize customers based on their FICO scores, and explore trends in loan purposes, debt-to-income ratios, and interest rates. The analysis includes data cleaning, transformation, visualization, and the export of results for further use.

## Table of Contents
- [Overview](#overview)
- [Project Features](#project-features)
- [Installation](#installation)
- [Dataset Description](#dataset-description)
- [Key Analysis and Insights](#key-analysis-and-insights)
- [Visualizations](#visualizations)
- [Output Files](#output-files)
- [Technologies Used](#technologies-used)

## Overview
The primary goal of this project is to perform an in-depth analysis of loan data and customer information. It involves identifying high-risk customers, categorizing FICO scores, analyzing loan purposes, and exploring relationships between financial factors such as debt-to-income ratio and annual income.

## Project Features
- Data cleaning to handle missing values and duplicates.
- Merging loan and customer datasets for comprehensive analysis.
- Categorization of loan purposes into broader categories (Financial, Educational/Business, Other).
- Risk assessment based on multiple financial parameters.
- FICO score categorization (Excellent, Very Good, Good, Fair, Poor).
- Identification of customers with high inquiries and public records.
- Visual exploration of loan purpose distribution, FICO score distribution, and risk patterns.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/loan-analysis.git
   ```
2. Navigate to the project directory:
  ```bash
   cd loan-analysis
   ```
3. Install the required Python libraries:
  ```bash
   cd loan-analysis
   ```
4. Place the datasets (loandataset.xlsx, customer_data.csv) in the project directory.

## Dataset Description
The project uses the following datasets:

  - loandataset.xlsx: Contains loan details such as purpose, annual income, debt-to-income ratio, FICO scores, and interest rates.
  - customer_data.csv: Includes customer information such as customer IDs and demographics.

## Key Analysis and Insights

- Loan Purpose:
  - Loans categorized into broader groups for analysis (Financial, Educational/Business, Other).
  - Visualization of the most common loan purposes.

- Risk Assessment:
  - Customers categorized as High Risk or Low Risk based on debt-to-income ratio, delinquencies, and credit utilization.

- FICO Score Distribution:
  - FICO scores categorized into Excellent, Very Good, Good, Fair, and Poor.
  - Insights into customer creditworthiness.

- Relationships Between Variables:
  - Scatterplots exploring the relationship between annual income and debt-to-income ratio.
  - Boxplots analyzing interest rates for high-risk vs low-risk customers.

- Visualizations
- Countplot:
  - Distribution of loan purposes.
- Scatterplot:
  - Debt-to-income ratio vs annual income.
- Histogram:
  - Distribution of FICO scores.
- Boxplot:
  - Interest rates by customer risk category.
 
## Output Files
The results are saved in an Excel file: Loan_analysis_results.xlsx, which includes:

* Cleaned and merged data.
* Loan purpose distribution.
* FICO score analysis.
* Risk assessment results.

## Technologies Used
* Python: Core programming language for data analysis.
* Libraries:
  - pandas: Data manipulation and analysis.
  - numpy: Numerical computations.
  - matplotlib and seaborn: Data visualization.
  - openpyxl: Writing results to Excel.
## Usage
1. Run the Jupyter Notebook to perform the analysis:
```bash
jupyter notebook loan_analysis.ipynb
```
2. Review the visualizations and insights generated in the notebook.
3. Access the exported Excel file (Loan_analysis_results.xlsx) for detailed analysis results.
