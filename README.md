📊 SQL Data Analytics Project
📌 Project Description
This project demonstrates a complete data analytics workflow using Microsoft SQL Server, focusing on transforming raw sales data into meaningful business insights through structured queries and analytical views.
The project applies Exploratory Data Analysis (EDA) and Advanced Analytics techniques to simulate a real-world data warehouse environment.

🏗 Project Architecture
The project follows a layered data approach:
Raw Data  →  Staging  →  Transformation  →  Analytics (Views)

Schema structure:
gold.fact_sales
gold.dim_products
gold.dim_customers

🔍 Exploratory Data Analysis (EDA)
The following analysis techniques are implemented:
Database Exploration
Dimensions Exploration
Date Analysis
Measures Exploration
Magnitude Analysis
Ranking (Top / Bottom N)

📈 Advanced Analytics
This project includes advanced analytical techniques such as:
Change Over Time (Trend Analysis)
Cumulative Analysis
Performance Analysis
Part-to-Whole Analysis
Data Segmentation
SQL-Based Reporting Views

⚙️ Tools & Technologies
Microsoft SQL Server
SQL Server Management Studio (SSMS)
T-SQL
CTEs & Window Functions

🚀 How to Run the Project
Restore the database backup.
Execute the scripts in this order:
Table creation scripts
Data loading scripts
View creation scripts
Run analytical queries from the gold views.

📊 Sample Views
SELECT * FROM gold.report_products;
SELECT * FROM gold.report_customers;
SELECT * FROM gold.report_sales;

🎯 Key Learning Outcomes
Data modeling using star schema
Writing optimized SQL queries
Creating reusable analytical views
Business-focused data storytelling

📎 Author

Abdallah Hussien
LinkedIn:abdallah-hussien-6633aa259
