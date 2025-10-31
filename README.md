# Sales-Insights-using-SQL-and-PowerBI


Project Overview

Sales Insights using SQL and Power BI is an end-to-end business intelligence project developed to analyze and visualize the sales performance of Nataraj Electronics for January 2025.
The objective of this project is to extract meaningful insights from raw transactional data using SQL and transform them into a visually interactive Power BI dashboard that supports data-driven decision-making.

Data Model Overview

The project is built on a relational data model with four key tables:

Table Name	Description
public_customers	Contains customer demographic details such as name, address, and city.
public_products	Holds product-related information including name, category, description, and MRP.
public_sales	Transaction table capturing sales quantity, selling price, sale date, and payment mode.
Date	Custom date dimension table containing Year, Month, Quarter, and Day attributes.
Relationships

public_sales[customer_id] → public_customers[customer_id]

public_sales[product_id] → public_products[product_id]

public_sales[sale_date] → Date[Date]

This star schema model enables efficient filtering, aggregation, and trend analysis.

Tools & Technologies Used
Tool / Technology	Purpose
SQL	Data cleaning, transformation, and creation of analytical queries.
Power BI	Data modeling, DAX calculations, and dashboard visualization.
Excel	Used for initial data verification and inspection.
DAX (Data Analysis Expressions)	To create calculated measures and KPIs.
Key Metrics and KPIs

Total Revenue: ₹5M

Total Customers: 188

Total Quantity Sold: 205

Average Sales per Customer: ₹28K

These KPIs were calculated using DAX expressions to measure sales performance and customer engagement for January 2025.

Dashboard Highlights

The Power BI Dashboard provides comprehensive insights into the company’s one-month sales operations.

Main Visuals

Revenue Overview – Displays total revenue, customers, quantity sold, and average sales per customer.

Sales by City – Highlights the most profitable regions; Sainthia leads with ₹4.3M revenue.

Sales Quantity by Payment Mode – Breaks down sales transactions by mode (Cash, EMI, UPI, etc.).

Revenue Trend by Date – Shows daily revenue performance for January 2025.

Sales by Category – Analyzes category-wise contribution such as Cooling, Kitchen, and Laundry appliances.

Top Products by Revenue – Identifies the top-performing products.

Top Salespersons – Displays sales contribution by individual representatives.


## Dashboard Snapshot

![Power BI Dashboard](./Snapshot%20of%20the%20Dashboard.png)



Key Insights

Cooling Appliances generated 71% of total revenue.

Cash accounted for the highest number of transactions (42%).

Split AC 1.5 Ton 5-star Inverter Series was the top-selling product, contributing ₹910K revenue.

Sainthia emerged as the highest revenue-generating city with ₹4.3M sales.

Sales were primarily concentrated in January 2025, indicating a short-term performance snapshot.

Snapshots
Customers Table

Date Table

Products Table

Sales Table

Power BI Dashboard

DAX Measures Used
Total Revenue = SUM(public_sales[selling_price])
Total Quantity Sold = SUM(public_sales[quantity])
Avg Sales per Customer = [Total Revenue] / DISTINCTCOUNT(public_sales[customer_id])

Process Workflow

Data Extraction:
Raw sales, customer, and product data imported into SQL.

Data Transformation:
Cleaned, validated, and standardized using SQL queries.

Data Modeling:
Relationships established among tables within Power BI.

Measure Creation:
DAX formulas applied to create KPIs and metrics.

Visualization & Insights:
Interactive dashboard developed to analyze monthly performance.

Learning Outcomes

Enhanced understanding of SQL-based data preparation.

Developed a data model and DAX measures for Power BI.

Created an interactive business dashboard highlighting KPIs and trends.

Strengthened analytical and storytelling skills using real-world sales data.

Author

Soham Das
Aspiring Data Analyst | SQL | Power BI | Excel | Python
📍 India
📧 [dasoham63@gmail.com]
🔗 LinkedIn Profile
 (https://www.linkedin.com/in/soham-das-884a1a315/)

Repository Information

Repository Name: Sales-Insights-using-SQL-PowerBi
Duration Covered: January 2025
Purpose: Portfolio project demonstrating SQL data analytics and Power BI visualization skills.
