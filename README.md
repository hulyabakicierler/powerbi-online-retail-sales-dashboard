Online Retail Sales Dashboard – Power BI
📌 Project Overview

This project is an end-to-end sales and returns analysis dashboard built using Power BI, based on the 2010–2011 Online Retail dataset.

The goal of the project is to practice the full analytics workflow — from SQL-based data preparation to DAX modeling and interactive dashboard design — while extracting meaningful business insights from transactional data.

🗂 Data Source

Dataset: Online Retail Transactions (2010–2011)

Source: Loaded into SQL Server and queried using SQL

Granularity: Invoice-line level transaction data

Key Fields: InvoiceDate, Country, CustomerID, Product Description, Quantity, UnitPrice, Returns

⚙️ Data Preparation (SQL)

Data cleaning and preparation were performed in SQL before loading into Power BI, including:

Handling missing and invalid dates

Creating derived fields such as:

Gross Sales

Returns Amount

Net Sales

Return indicators

Ensuring correct data types for analytical modeling

📊 Power BI Modeling & DAX

Key DAX measures created in Power BI include:

Gross Sales

Returns Amount

Net Sales

Return Rate

Order Count

Total Quantity

These measures were used to support KPI reporting, trend analysis, and comparative visuals.

📈 Dashboard Structure
Page 1 – Sales Overview

This page provides a high-level business view:

KPI cards for Gross Sales, Net Sales, Returns Amount, and Return Rate

Monthly Net Sales trend analysis

Top 10 Countries by Net Sales

Top 10 Products by Net Sales

Comparison of Net Sales vs Returns at product level

Purpose: Quickly assess overall performance and identify major revenue drivers.

Page 2 – Product & Returns Analysis

This page focuses on risk-aware product performance:

Top-selling products by Net Sales

Products with high Net Sales but elevated return amounts

Top products by Return Rate

Purpose: Identify products that contribute strongly to revenue but may require attention due to return behavior (e.g., quality issues, customer expectations, or logistics).

🔍 Key Insights

Revenue is highly concentrated in a small number of countries

Several top-selling products also show disproportionately high return rates

Sales growth alone is not sufficient to evaluate performance without considering returns

Return behavior provides important signals for operational and product-level improvements

🧠 Learning Outcomes

Through this project, I practiced:

SQL-based data preparation for BI tools

Writing and applying DAX measures

Designing clear and business-oriented dashboards in Power BI

Translating raw transactional data into actionable insights

🚀 Tools & Technologies

SQL Server

Power BI

DAX

Data Visualization & BI Concepts
