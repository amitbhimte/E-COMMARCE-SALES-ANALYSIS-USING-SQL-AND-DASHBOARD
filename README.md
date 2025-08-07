#Project Overview
In this project, I started by collecting raw sales data from an e-commerce dataset. The first step was to clean and format the data using SQL — including fixing date formats, checking for consistency, and preparing the dataset for analysis. After cleaning, I wrote multiple SQL queries to explore different aspects of the business such as sales trends, customer behavior, product performance, and payment preferences.

Once the data was well-structured and meaningful insights were generated, I used Power BI to create a dashboard that visualizes key metrics and trends in a clear, interactive format.
Tools & Technologies
SQL (MySQL) – Used for cleaning data, formatting dates, and performing analysis through aggregation, filtering, and window functions

Power BI Desktop – Built the dashboard and visualizations

Power Query – Shaped and loaded data into Power BI

DAX – Created calculated columns and custom KPIs

File Types – .txt for SQL scripts, .pbix for the Power BI dashboard

🧾 SQL Process Overview
Key data preparation and analysis tasks included:

Formatting Order Date using STR_TO_DATE() and converting to date type

Calculating total and daily sales

Comparing month-over-month sales and orders

Finding average daily sales for May

Identifying above/below average sales days

Segmenting weekday vs weekend performance

Aggregating sales by state, city, category, and sub-category

Ranking top-selling products and top-paying customers

All SQL queries used are available in the file: SALES_SQL_QUERIES.txt

📊 Dashboard Highlights
The Power BI dashboard contains visuals that answer business questions like:

What are the total sales, profit, and average order value?

Which customers generate the most revenue?

Which states and cities have the highest sales?

Which product categories are most popular?

How does monthly profit trend over time?

Which payment methods are most used?

Users can interact with filters to focus on specific quarters, regions, or categories.

💡 Key Insights
Highest monthly profit was observed in March, while February had the lowest

Clothing is the most sold category, contributing 67% of total quantity

COD is the most preferred payment mode

Top customers include Hitesh, Shruti, Tulika, and Anurag

Printers and Chairs were among the most profitable sub-categories
