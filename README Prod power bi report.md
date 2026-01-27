📦 Power BI Inventory KPI Analysis Project (SQL Server → MySQL Migration)
📌 Project Overview

This project demonstrates how a Power BI report behaves during a data source transition, while ensuring that business KPIs remain unchanged.

The report is built on an Inventory dataset and focuses on creating DAX-driven KPIs and validating them while migrating the data source from Microsoft SQL Server to MySQL.

The project closely simulates a real enterprise scenario, where organizations:

Move from one database technology to another

Shift between test and production environments

Must ensure data consistency and accuracy after migration

🗄 Data Sources

Initial Data Source: Microsoft SQL Server

Target Data Source: MySQL Database

Dataset: Inventory Data

The underlying data remains the same; only the data source and connection logic change.

📊 Report Structure

The Power BI report contains two pages, showcasing six key business KPIs:

1️⃣ Inventory Overview – Page 1

KPIs displayed:

Average Demand per Day

Average Availability per Day

Total Supply Shortage

These KPIs provide operational insights into inventory performance.

2️⃣ Financial Impact – Page 2

KPIs displayed:

Total Profit

Total Loss

Average Daily Loss

These KPIs highlight the financial implications of inventory gaps and shortages.

🔧 Key Technical Concepts Covered
🔹 DAX Measures

Although the KPIs appear simple, they are created using multiple DAX measures to:

Capture daily averages

Calculate shortages and losses

Maintain consistency across data source changes

The project demonstrates how robust DAX logic ensures KPIs remain accurate during migration.

🔹 SQL Data Preparation

SQL code written in Microsoft SQL Server

Use of JOIN operations to prepare the dataset

Business-ready data modeling before reporting

🔹 Data Source Migration

This project covers two types of transitions:

Test → Production environment in Microsoft SQL Server

Microsoft SQL Server → MySQL Database

The migration is handled by:

Modifying the connection logic in Power Query Editor

Updating the Advanced Editor code

Repointing the report to the new data source without breaking visuals or measures

🔹 MySQL Query Translation

Writing equivalent SQL logic in MySQL

Ensuring functional parity between SQL Server and MySQL queries

Understanding syntax differences across databases

✅ Data Validation

Data validation is a critical part of this project.

Key validation principles:

The underlying data does not change

Only the data source changes

KPI values must remain identical

Validation steps include:

Comparing KPI outputs before and after migration

Verifying totals, averages, and financial metrics

Ensuring business trust in migrated reports

🚀 Power BI Service Deployment

Publishing the report to Power BI Service

Verifying results post-deployment

Ensuring refresh works correctly with the new data source

🎯 Key Features

Data source migration scenario

SQL Server to MySQL transition

DAX-driven KPI stability

Inventory and financial analysis

Real-world validation workflow

Interview-relevant BI concepts

🛠 Tools & Technologies

Power BI Desktop

Power BI Service

Microsoft SQL Server

MySQL

Power Query Editor

DAX

SQL

📈 Learning Outcomes

Confidence in handling data source migrations

Strong understanding of Power Query Advanced Editor

Ability to validate KPIs after backend changes

Real-world experience with SQL Server and MySQL

Interview-ready Power BI project explanation
