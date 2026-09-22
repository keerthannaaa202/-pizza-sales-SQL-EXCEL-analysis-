🍕 Pizza Sales Analysis — SQL & Excel

Analysis of a pizza restaurant's sales data using SQL for querying/KPI calculation and Excel for dashboard visualization. The project covers 21,000+ orders across multiple pizza categories and sizes.

📌 Project Overview

The goal of this project is to analyze pizza sales data to uncover key business insights — revenue trends, best/worst performing products, order patterns by day and hour, and sales distribution by category and size — to support data-driven decision making.

🛠 Tools Used
MySQL Workbench — writing & running SQL queries, KPI calculation, aggregation
Excel — data connection, pivot tables, charts, dashboard building
🔄 Project Workflow
Data Querying (MySQL Workbench) — Wrote and executed SQL queries in MySQL Workbench to calculate KPIs (Total Revenue, Total Orders, Total Pizzas Sold, AOV, Avg Pizzas/Order) and generate chart-ready data (daily/hourly trends, category & size-wise sales, best/worst sellers).
Connecting MySQL to Excel (ODBC) — Set up MySQL ODBC Connector/ODBC Driver and created a DSN (Data Source Name) to connect Excel directly to the MySQL database, allowing live query results/tables to be pulled into Excel for analysis.
Data Import — Imported the query output data from MySQL into Excel as structured tables.
Pivot Tables — Built pivot tables in Excel on top of the imported data to summarize and slice the data by category, size, day, and hour.
Dashboard Creation — Used the pivot tables to create charts (bar, line, pie) and combined them into a single interactive Excel dashboard showing all KPIs and trends at a glance.
📊 Key Performance Indicators (KPIs)
KPI	Value
Total Revenue	$817,860.05
Total Orders	21,350
Total Pizzas Sold	49,574
Average Order Value	$38.31
Average Pizzas Per Order	2.32
📈 Charts & Analysis
Daily Trend for Total Orders — order volume by day of the week
Hourly Trend for Total Orders — order volume by hour of day
Percentage of Sales by Pizza Category — revenue share across Classic, Chicken, Supreme, Veggie
Percentage of Sales by Pizza Size — revenue share across S/M/L/XL/XXL
Total Pizzas Sold by Pizza Category
Top 5 Best Sellers — by total pizzas sold
Bottom 5 Worst Sellers — by total pizzas sold
💡 Key Insights
Friday has the highest order volume (3,538 orders), while Sunday has the lowest (2,624 orders) — a strong indicator of weekend/end-of-week demand.
Classic pizzas generate the highest revenue (~$220K), closely followed by Supreme (~$208K), with Chicken and Veggie close behind.
Average customers order just over 2 pizzas per order, spending an average of $38.31 per order.
📂 Repository Structure
├── README.md
├── SQL_Queries/
│   └── pizza_sales_queries.sql        # All KPI & chart queries
├── Excel_Dashboard/
│   └── Pizza_Sales_project.xlsx       # KPI sheet, charts, pivot tables
├── Screenshots/
│   └── dashboard_preview.png          # Dashboard/chart screenshots
🚀 How to Use
Clone/download the repo.
Import the pizza sales dataset into MySQL Workbench.
Run the queries in pizza_sales_queries.sql to generate the KPIs and chart data.
Install MySQL ODBC Driver, set up a DSN, then in Excel go to Data → Get Data → From Other Sources → From ODBC, select the DSN, and connect to the MySQL database.
Open Pizza_Sales_project.xlsx to explore the pivot tables, charts, and final dashboard.
📬 Contact

Feel free to connect with me on (https://www.linkedin.com/in/keerthana-anbusekar-1b109127b/) or reach out for feedback/collaboration!

⭐ If you found this project useful, consider giving it a star!
