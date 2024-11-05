# Financial Data Analysis SQL Project

This project provides SQL scripts for analyzing financial data, with a focus on income and expense records. It enables creating daily financial summaries, calculating monthly growth rates, and detecting outliers in the data.

## Overview

This SQL project is designed for financial and data analysts working with large income and expense datasets. The scripts perform essential data analysis tasks such as:
- Daily financial summary generation
- Monthly income and expense growth rate calculations
- Statistical outlier detection

## Database Schema

The project includes three tables:

1. **`income`** - Stores individual income records.
   - **Columns:** `id`, `date`, `amount`, `source`

2. **`expense`** - Stores individual expense records.
   - **Columns:** `id`, `date`, `amount`, `category`

3. **`financial_status`** - Summarizes daily financial data with total income, expense, and net profit.
   - **Columns:** `date`, `total_income`, `total_expense`, `net_profit`

## Key SQL Operations

1. **Daily Financial Status Calculation**  
   Calculates and inserts daily total income, total expense, and net profit into `financial_status`.

2. **Monthly Growth Rate Calculation**  
   Compares current month’s data to the previous month to calculate growth rates for both income and expenses.

3. **Outlier Detection**  
   Computes the average and standard deviation for income and expense data, helping to identify statistical outliers.

## Usage

- Import the SQL script into your SQL environment.
- Run the provided queries to create the database tables and perform the analyses.
- Update data as needed to perform ongoing financial analysis.

