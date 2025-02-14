# Data-Rangling-project
Data Rangling project using python
# Supermarket Data Wrangling & Business Insights

## Overview
This project focuses on cleaning, transforming, and analyzing a supermarket sales dataset to extract actionable business insights. The dataset includes transaction records with details such as unit prices, quantities, totals, taxes, dates, times, ratings, payment methods, and city information.

## Purpose
- **Data Wrangling:** Clean and transform raw data by handling missing values, converting data types, removing duplicates, and standardizing formats.
- **Business Insights:** Analyze the cleaned data to uncover trends in sales, customer behavior, and operational performance, and provide recommendations for business improvements.

## Dataset Details
- **Location:** `data/supermarket_sales.xlsx`
- **Size:** *[Replace with actual number of rows and columns, e.g., "1,000 rows and 10 columns"]*
- **Key Columns:**
  - `Unit Price` (converted from object to float)
  - `Quantity`
  - `Total`
  - `Tax 5%` (calculated as 5% of `Total` when missing)
  - `Date` (standardized to `YYYY-MM-DD`)
  - `Time` (standardized and filled with "8:30" for missing values)
  - `Rating` (customer ratings on a scale from 1 to 5)
  - City indicator columns (`Yangon`, `Naypyitaw`, `Mandalay`) are used to create a unified `City` column

## Project Structure
