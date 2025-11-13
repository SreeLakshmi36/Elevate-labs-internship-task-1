# Elevate-labs-internship-task-1
task 1
his folder contains my Data Analyst Internship Task 1 submission.

I performed complete data cleaning on the Sales Data Sample dataset including:
- Fixing encoding errors during file loading
- Removing duplicate entries
- Handling missing values in STATE, TERRITORY, and POSTALCODE
- Normalizing column names (lowercase + snake_case)
- Converting ORDERDATE to datetime format
- Converting quantityordered, priceeach, orderlinenumber, and sales to numeric types
- Filling sales values using quantity * price when needed
- Standardizing text fields such as status, country, dealsize, and city
- Cleaning postal codes by removing trailing .0

The final cleaned dataset (cleaned_sales_data.csv) has:
- No duplicate rows
- No missing values in important fields
- Correct data types
- Standardized and consistent formatting
