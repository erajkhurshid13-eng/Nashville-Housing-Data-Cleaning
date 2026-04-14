# Nashville-Housing-Data-Cleaning
A data cleaning project using SQL to prepare a real-world
housing dataset for analysis.
What this project does
Raw data is rarely clean. This project takes the Nashville
Housing dataset and works through the most common data quality
problems you encounter before any real analysis can begin.
Problems solved
Standardized date formats
Populated missing property addresses using self joins
Split combined address fields into separate columns
(address, city, state)
Replaced Y/N values with readable Yes/No labels
Removed duplicate records using ROW_NUMBER()
Dropped unused columns
Tools used
SQL (Microsoft SQL Server)
Why this matters
Data cleaning is where most data projects actually live.
Getting this right before building models or dashboards is
what separates reliable analysis from misleading output.
This project is a practical demonstration of that process
on a real dataset.
Dataset
Nashville Housing Data - publicly available dataset commonly
used for SQL data cleaning practice.
