# Project 1 — Data Cleaning and Preparation

## Project Overview

This project focuses on cleaning and preparing an e-commerce sales dataset for further analysis.

The goal was to identify common data-quality issues, address them appropriately, and validate the dataset before analysis.

## Tools Used

- Microsoft Excel
- Power Query

## Dataset Overview

- **Records:** 1,200
- **Columns:** 14
- **Dataset:** E-Commerce Sales Dataset

## Data Quality Checks

| Check | What I Found | What I Did |
|---|---|---|
| **Dataset Structure** | 1,200 records across 14 columns | Confirmed the dataset structure was intact |
| **Duplicate Records** | No duplicate rows found | No changes required |
| **Missing Data** | `CouponCode` had 309 missing values (25.75%) | Replaced missing values with `None` |
Date Format | Dates were correctly parsed as datetime64[ns] | Retained the correct date data type
| **Price Calculation** | `TotalPrice` matched `Quantity × UnitPrice` | Verified all records; no calculation errors found |
| **Quantity Values** | Values ranged from 1 to 5 | No negative or obviously invalid values found |
| **Unit Price Values** | Values ranged from 11.39 to 699.93 | No negative or obviously invalid values found |

## Cleaning Process

The following steps were carried out:

1. Inspected the dataset structure and data types.
2. Checked for duplicate records.
3. Identified missing values.
4. Handled missing `CouponCode` values.
5. Verified the `Date` field.
6. Validated `TotalPrice` against `Quantity × UnitPrice`.
7. Reviewed numerical fields for invalid values.

## Final Result

The dataset was cleaned and validated while preserving all **1,200 records and 14 columns**.

- **0 duplicate records**
- **309 missing CouponCode values handled**
- **0 TotalPrice calculation errors**
- **No negative or obviously invalid Quantity or UnitPrice values identified**

## Project Files

- `Dataset_for_Data_Analytics.csv` — Original dataset
- `Project_1_Cleaned_ECommerce_Sales.csv` — Cleaned dataset
- `Basit_Rasaq_Oluwatobi_Project_1_Data_Cleaning.pdf` — Data cleaning documentation

## Key Takeaway

This project demonstrates a practical approach to **data cleaning, data validation, and preparation** before performing analysis.
