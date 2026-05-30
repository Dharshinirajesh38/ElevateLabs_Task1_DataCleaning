# Elevate Labs - Data Analyst Internship Task 1

## Task Objective

Clean and prepare a raw dataset by handling missing values, duplicates, inconsistent formatting, and data type issues.

## Dataset Used

Customer Personality Analysis (marketing_campaign.csv)

## Tools Used

* Python
* Pandas
* Jupyter Notebook

## Data Cleaning Steps Performed

1. Loaded the dataset into Pandas.
2. Identified missing values using `isnull()`.
3. Filled missing values in the Income column using the median value.
4. Checked and removed duplicate records.
5. Standardized column names by converting them to lowercase and replacing spaces with underscores.
6. Standardized text values in categorical columns.
7. Converted `dt_customer` to datetime format.
8. Verified and corrected data types.
9. Saved the cleaned dataset as `cleaned_marketing_campaign.csv`.

## Deliverables

* Original Dataset (`marketing_campaign.csv`)
* Cleaned Dataset (`cleaned_marketing_campaign.csv`)
* Jupyter Notebook (`Task1_DataCleaning.ipynb`)
* Screenshots of the cleaning process

## Summary of Changes

* Missing values handled successfully.
* Duplicate rows removed.
* Column names standardized.
* Text formatting standardized.
* Date format converted to datetime.
* Data types verified and corrected.
* Dataset prepared for further analysis and visualization.
