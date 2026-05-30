# Task 1: Data Cleaning and Preprocessing

## Project Overview
This task involves cleaning a raw customer personality dataset using Microsoft Excel. The original dataset contained missing values, inconsistent categories, invalid ages, and outliers.

## Files Included
- `raw_data/marketing_campaign.csv` - Original raw dataset
- `cleaned_data/Hassan_El_Miari_cleaned_marketing_campaign.csv` - Cleaned dataset
- `summary_of_changes.txt` - Detailed list of all cleaning steps

## Tools Used
- Microsoft Excel (no Python)

## Cleaning Steps Summary
1. Filled missing Income values with median
2. Removed rows with invalid birth years (<1905)
3. Standardized Marital Status (YOLO/Absurd/Alone → Single)
4. Standardized Education (2n Cycle → Bachelor, Basic → High School)
5. Removed outlier with Income = 666,666
6. Converted column headers to lowercase

## How to Use
Open the cleaned CSV file in Excel or any data analysis tool. The data is now ready for analysis, visualization, or modeling.

## Key Learnings
- Using Excel's conditional formatting to find blanks
- Using Find/Replace to standardize text values
- Using Remove Duplicates to check for duplicate rows
- Using box and whisker charts to identify outliers
- Using =LOWER() function to clean column headers

## Submission Date
May 30, 2026