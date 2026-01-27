🏥 Power BI Clinical Data Analytics Project (Microsoft SQL Server)
📌 Project Overview

This project showcases a large-scale, end-to-end Business Intelligence solution built using Microsoft SQL Server as the primary data source and Power BI for reporting and visualization.

A key highlight of this project is the data volume — the dataset contains 20 million records (2 crore rows), making it a realistic simulation of enterprise-level data processing and analytics.

The project focuses on:

Large dataset generation

Data profiling and cleaning using SQL

Performance-aware data loading into Power BI

Clinical data analysis across hospitals and time

🗄 Data Source

Database: Microsoft SQL Server

Data Volume: ~20,000,000 records

Domain: Clinical / Healthcare Analytics

The dataset was programmatically created and transformed using SQL, making this project especially valuable for interview discussions.

🔧 Data Preparation & SQL Concepts
🔹 Data Generation (20 Million Records)

The project includes a detailed explanation of how large-scale data was created, which is often asked in interviews.

Key SQL concepts used:

Dynamic SQL

Row generation techniques

Randomized data creation for realistic scenarios

🔹 SQL Functions Used

The following SQL functions were used both for data generation and data transformation:

DATEADD()

DATEDIFF()

CHECKSUM()

NEWID()

ABS()

These functions helped in:

Creating date-based fields

Generating random but controlled values

Simulating real-world clinical datasets

🧹 Data Cleaning & Transformation
🔹 In Microsoft SQL Server

Data profiling using SQL queries

Data type corrections

Cleaning invalid and inconsistent values

Preparing analysis-ready tables before loading into Power BI

🔹 In Power BI (Power Query Editor)

Changing data types

Basic transformation and validation

Ensuring compatibility with Power BI data model

⚙️ Power BI Data Loading & Troubleshooting

While loading the large dataset into Power BI Desktop, certain data load issues were encountered.

These were resolved by:

Adjusting Data Source Settings

Troubleshooting in Report View

Optimizing load behavior for large datasets

This part of the project reflects real-world BI problem-solving scenarios.

📊 Report Pages & Analysis
1️⃣ Clinical Analysis by Hospital

Analysis by Hospital ID

Key metrics displayed:

Number of Admissions

Number of Readmissions

Number of Infections

Number of Deaths

Comparative analysis across hospitals and years

2️⃣ Time-Based KPI Analysis

KPIs analyzed over time

Trend-based insights

Year-wise performance monitoring

Helps identify patterns and anomalies in clinical outcomes

🚀 Power BI Service Deployment

Report published to Power BI Service

Post-publishing changes made in Power BI Desktop

Existing report in workspace was replaced with updated version

Demonstrates real-world report lifecycle management

🎯 Key Features

Large-scale dataset (20 million rows)

SQL-driven data generation and cleaning

Clinical KPI analysis

Hospital-wise and time-based insights

Data load troubleshooting experience

End-to-end BI workflow

🛠 Tools & Technologies

Microsoft SQL Server

SQL (Dynamic SQL & Functions)

Power BI Desktop

Power Query Editor

Power BI Service

📈 Learning Outcomes

Hands-on experience with large datasets

Strong SQL data profiling and transformation skills

Understanding Power BI performance considerations

Real-world troubleshooting of data load issues

Confidence in explaining large-scale BI projects in interviews
