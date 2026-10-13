# SWYNEX Data Cleaning & Preparation (Task 1)

## Overview
This repository contains the data cleaning and preparation work completed for Task 1 of the SWYNEX Data Analysis Internship.

## Dataset Description
- **Dataset Name:** E-commerce Sales Analytics (`ecommerce_sales_analytics_5000.csv`)
- **Source:** Public E-commerce Sales Dataset
- **Tools Used:** Microsoft Excel / WPS Office

## Key Data Cleaning & Preparation Steps
1. **Structural Alignment & Parsing:** Used Excel's "Text to Columns" tool with comma separation and standard decimal delimiters (`.`) to parse all columns correctly without column shifts.
2. **Data Type Fixes & Formatting:**
   - Standardized `customer_rating` and prices to numeric formats, preventing Excel from auto-converting decimal numbers into calendar dates.
   - Standardized `order_date` values to a unified date format.
3. **Duplicate Verification:** Checked dataset integrity using the "Remove Duplicates" tool (no duplicate records found).
4. **Data Validation:** Verified logical values across `quantity`, `unit_price`, `discount`, `payment_method`, `delivery_days`, `customer_rating`, and `revenue`.

## Files Included
- `cleaned_ecommerce_sales.xlsx` - Cleaned and formatted dataset
- `README.md` - Documentation of the cleaning methodology
