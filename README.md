# Power-BI-Sales-Analysis-with-SQL-and-Python-Data-Processing-Visualization-and-Insights

📊Overview

This project focuses on analyzing sales data using Power BI. The dataset was initially stored in multiple Excel files, then processed and uploaded into a SQL database using Python. During the SQL data extraction phase, JOIN operations were used to combine multiple tables into a unified dataset for analysis. Finally, the data was visualized and analyzed in Power BI using a combination of DAX measures and calculated columns to extract meaningful insights such as total sales, loss rate, and total returns.

📊Tech Stack
Python (for data processing and SQL upload)
SQL (for structured data storage and querying)
Utilized JOIN operations to integrate multiple tables and create a comprehensive dataset.
Power BI (for data visualization and analysis)
Used DAX measures and calculated columns for advanced data calculations and analysis.
📂 Project Workflow
1️⃣ Data Preparation (Excel → SQL)
The raw sales data was stored in four Excel files.
Using Pandas and SQLAlchemy in Python, the data was cleaned and uploaded into a SQL database.
JOIN operations were used in SQL to merge data from different tables (e.g., sales transactions, product details, and categories) into a single dataset suitable for analysis.
2️⃣ Data Extraction (SQL → Power BI)
Power BI was used to connect to the SQL database and extract the structured data.
The SQL query results, which were enriched with JOIN operations, provided a comprehensive dataset for reporting.
3️⃣ Data Analysis & Visualization
Various DAX measures and calculated columns in Power BI were created to analyze key metrics:

Total Sales → Created as a measure to sum up the value of successful sales transactions, excluding returns.
Total Returns → A measure to calculate the amount of returned sales.
Loss Amount → A calculated column that determines the difference between wholesale price and selling price, multiplied by the quantity sold.
Loss Rate → A measure to calculate the percentage of loss in relation to total sales.
Return Rate → A measure to calculate the ratio of returned products to total sales.
4️⃣ Insights and Reporting
Visual dashboards were created to monitor sales trends, loss rates, and return patterns over time.
Category and product-level analyses were conducted to identify high-loss or high-return items.
Time-Series Trends and Sales Performance Dashboard were created to monitor sales fluctuations, return rates, and loss patterns.

📊 Key Visuals in Power BI
1. Card Visual
2. Filtered Sales Analysis
3. Sales Analysis by Category
4. Sales and Pricing Analysis by Discount and Sale/Return
5. Total Profit Analysis by Category, Year, and Month
6. Comprehensive Sales and Return Analysis by Category
7. Total Loss Rate per Category
