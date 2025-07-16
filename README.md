# 📊 Sales Insights Dashboard using SQL + Power BI

This project delivers a powerful end-to-end **Sales Insights Dashboard** using SQL for data cleaning and querying, and Power BI for data visualization. The analysis uncovers patterns across markets, products, and customers—enabling data-driven business decisions.


## 🎯 Project Objective

To identify key sales trends, regional performance, customer behavior, and product-level revenue contributors by:
- Cleaning and transforming raw sales data using SQL
- Creating interactive visualizations in Power BI
- Generating actionable business insights


## 🛠️ Tools & Technologies

- SQL – For data cleaning, transformation, and querying
- Power BI – For visual dashboard creation and trend analysis
- Excel – For initial data formatting and CSV handling


## 📈 Dashboard Preview

![Sales Dashboard](https://github.com/antima0401/sales_insights_powerbi_dashboard/blob/main/documents/dashboard_screenshot.png?raw=true)


## 📊 Key Business Insights

- 💰 Total Revenue: ₹987M | Total Sales: 2M units
- 🏙️ Top Performing Market: Delhi NCR dominates both sales and revenue
- 📦 Best-Selling Products: `Prod040` and `Prod159` lead in contribution
- ⏳ Trend: Revenue peaked in early 2018 and declined by 2020—indicating seasonal or macroeconomic influence
- 🛍️ Top Customers: Electrosalara Stores and Premium Stores are top contributors to revenue


## 🧩 Dashboard Features

- 🔄 Filter by **Year (2017–2020)** and **Month**
- 📊 Visuals include:
  - Top 5 customers
  - Revenue by market
  - Sales by market
  - Product-wise revenue
  - Monthly revenue trend
- 🧠 Drill-down capability to explore trends at a granular level


## 🛠️ How to Reproduce This Project

1. Import `raw_sales_data.csv` into a SQL environment (MySQL, PostgreSQL, etc.)
2. Run the queries in `sql_queries/data_cleaning.sql` to clean and structure the data
3. Export the result as `cleaned_sales_data.csv`
4. Load the cleaned data into Power BI using the `.pbix` file
5. Explore filters, visuals, and insights


## 💼 Business Value

This dashboard helps:
- Identify revenue-driving products and customers
- Detect underperforming markets
- Support inventory and marketing planning
- Monitor revenue over time for better forecasting
