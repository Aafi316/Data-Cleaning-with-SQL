🧹 Housing Data Cleaning Project

📖 Project Overview

This project focuses on cleaning a raw housing dataset using SQL Server to prepare it for reliable analysis and reporting. The main goals were to eliminate inconsistencies, blanks, and redundant data, ensuring a clean and structured dataset ready for downstream analytics or visualization tasks.

🎯 Objectives

Identify and remove blank values and null records

Eliminate duplicate entries and redundant columns

Standardize data formats (e.g., dates, numeric fields)

Improve overall data quality and usability

🛠️ Tools & Technologies

SQL Server – For all data cleaning and transformation operations

🧪 Cleaning Steps

Null & Blank Value Handling

Identified critical fields (e.g., price, location, property type)

Removed rows with missing or invalid key information

Duplicate Removal;

Detected and deleted duplicate rows based on unique identifiers and matching field combinations

Removed duplicate or unnecessary columns in the dataset schema

Data Type Standardization;

Ensured date fields were stored in DATE or DATETIME format

Converted monetary and numerical fields to appropriate numeric types

Column Renaming & Formatting;

Renamed columns for clarity and consistency (e.g., house_price instead of hp, listing_date instead of ld)

Trimmed leading/trailing whitespace from text fields

✅ Outcome

The result is a clean, consistent, and analysis-ready housing dataset. All rows contain complete essential data, duplicates have been removed, and the schema has been standardized for clarity and usability in future reporting or data science workflows.

🚀 Next Steps

Load the cleaned dataset into Power BI or Excel for exploratory data analysis

Enrich with external data (e.g., regional pricing trends, mortgage rates)

Automate the cleaning workflow using stored procedures or scheduled ETL jobs
