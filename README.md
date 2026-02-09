Interactive Power BI dashboard and SQL scripts analyzing Amazon sales across cities with product, customer, and revenue insights.

This repository presents a comprehensive sales analysis project using both SQL and Power BI. The objective is to analyze Amazon’s transactional sales data across multiple cities (Mandalay, Yangon, Naypyitaw) to uncover customer trends, product performance, and revenue insights.

The project is divided into two main components:

SQL Analysis → Data modeling, cleaning, transformation, and answering 20+ business questions.

Power BI Dashboard → Interactive visualizations for decision-making.

🔍 Key Insights

City-wise revenue and sales performance

Best and worst performing product categories

Customer segmentation by type and gender

Peak sales times (time of day, day of week, month)

Payment method preferences

VAT (Tax) analysis across cities and customer types

🗂️ Repository Structure amazon-sales-analysis/

├── amazon sales dashboard.pbix # Power BI dashboard file

├── sales_analysis.sql # SQL scripts (DB creation, cleaning, queries)

└── README.md # Project documentation

🛠️ Tools & Technologies

SQL (MySQL) → Data modeling, cleaning, transformation, and analysis

Power BI Desktop → Interactive dashboards & data visualization

Power Query → Data wrangling & preprocessing

📊 Data Model

The dataset includes transactional details such as:

Invoice Details: Invoice ID, City, Branch

Customer Information: Type, Gender

Product Information: Product line, Unit Price, Quantity

Financials: COGS, Tax, Total, Gross Income

Transaction Info: Date, Time, Payment Method, Customer Rating

🚀 Getting Started

SQL Setup

Import and execute sales_analysis.sql in MySQL Workbench (or any SQL client).

The script will:

Create the database amazon_sales.

Build the amazon_transactions table.

Add calculated columns (timeofday, dayname, monthname).

Run analytical queries to answer 20+ business questions.

Power BI Dashboard

Open amazon sales dashboard.pbix in Power BI Desktop.

Explore the dashboard using interactive filters and slicers.

Gain insights on city-wise, product-wise, and customer-wise sales.

📷 Dashboard Preview

Screenshot 2025-09-27 141900
📌 Business Questions Answered (SQL)

Some of the key queries addressed in sales_analysis.sql:

Which city generated the highest revenue?

Which product line had the highest sales and revenue?

What are the peak sales times (morning, afternoon, evening)?

Which customer type contributed the most to revenue?

Which payment method was most preferred?

What is the average rating per product line?
