☁️ Power BI Analytics Project (Amazon Athena & ODBC)
📌 Project Overview

This project demonstrates how to build a full-scale Power BI report using cloud-based data sources, specifically Amazon Athena accessed via ODBC.

The project goes beyond simple report creation and focuses heavily on:

End-to-end cloud data source setup

Complex data cleaning and transformation

Advanced Power BI features such as bookmarks, custom visuals, and small multiples

Real-world troubleshooting and optimization

By the end of this project, you will be able to create a four-page, visually rich Power BI report using non-traditional data sources.

🔗 Data Sources

This project uses two data access methods:

ODBC

Amazon Athena

☁️ AWS Setup & Configuration

Since Amazon Athena requires extensive backend setup, this project covers the full process, including:

Configuring AWS Glue

Creating and managing IAM users

Setting up permissions

Downloading and installing the Simba Athena ODBC Connector

Connecting Power BI Desktop using the Amazon Athena connector

Although such setups are often handled by platform teams in real projects, this project ensures you understand the entire workflow end to end.

🧹 Data Cleaning & Transformation

Data preparation is a major focus of this project.

Key Highlights:

Extensive data cleaning in Power Query Editor

Handling data load issues

Troubleshooting at:

Source level (Athena)

Power BI level (Power Query)

Special Focus:

Cleaning a complex Year column

Dedicated deep-dive transformation steps

Use of Unpivot functionality to reshape data for reporting

📊 Report Structure

The Power BI report consists of four pages:

1️⃣ Page 1 – Bookmark-Based Analysis

Interactive visuals controlled using bookmarks

No slicers used

User-driven navigation through bookmarks

2️⃣ Page 2 – Slicer-Based Analysis

Similar visual layout to Page 1

Uses slicers instead of bookmarks

Requires different data preparation logic

Built on an unpivoted dataset

This contrast helps understand when to use bookmarks vs slicers in real projects.

3️⃣ Page 3 – Advanced Visual Analysis

Enhanced formatting

Business-focused insights

Improved visual storytelling

4️⃣ Page 4 – Trend & Small Multiples Analysis

Line charts with small multiples

Trend comparison across categories

Designed for scalable, comparative analysis

📈 Visualizations Used

KPI visuals

Line charts

Radar chart (custom visual from AppSource)

Small multiples

Bookmark-based navigation

Slicer-based filtering

Note: The radar chart is not available by default in Power BI and is imported from AppSource.

🎨 Report Design & Formatting

Custom background images (provided in resources)

Filters pane and filter card formatting

Clean, professional layout

Consistent visual theme across pages

🔖 Bookmarks & Navigation

Creation and management of bookmarks

Bookmark navigators

Comparison of bookmark-based vs slicer-based interactivity

🚀 Deployment

Report published to Power BI Service

End-to-end lifecycle from cloud data source → Power BI Desktop → Power BI Service

🎯 Key Features

Amazon Athena integration with Power BI

ODBC connectivity

Full AWS backend setup understanding

Heavy Power Query transformations

Unpivot-based modeling

Bookmarks vs slicers comparison

Custom visuals from AppSource

Multi-page enterprise-style report

🛠 Tools & Technologies

Power BI Desktop

Power BI Service

Amazon Athena

AWS Glue

AWS IAM

ODBC (Simba Connector)

Power Query Editor

AppSource Custom Visuals

📈 Learning Outcomes

Strong understanding of cloud-based BI integration

Confidence working with Amazon Athena

Advanced Power Query transformation skills

Ability to troubleshoot real-world data issues

Interview-ready explanation of complex BI projects
