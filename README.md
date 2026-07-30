💳 UPI Transactions Analysis Dashboard | Power BI

📌 Project Overview

This project is an interactive Power BI dashboard built to analyze UPI transaction data. The dashboard provides insights into transaction trends, remaining account balances, customer demographics, and transaction behavior across different cities and currencies.
The project demonstrates end-to-end Power BI development, including data cleaning, data profiling, DAX calculations, interactive visualizations, slicers, bookmarks, and dashboard navigation.

🎯 Objectives
Analyze monthly UPI transaction performance.
Monitor monthly remaining account balance.
Compare transaction amount and balance across cities and currencies.
Segment customers using Age Groups.
Build an interactive dashboard for business users.

📂 Data Source
Source: Excel Workbook (.xlsx)
Tool Used: Microsoft Power BI Desktop

🛠️ Data Preparation
  Data Profiling
Performed data profiling in Power Query to:

Check data quality
Identify null values
Review column distributions
Validate data types
Detect inconsistencies

📊 Data Transformation

Created a New Age Group column using DAX:

Age Group =
IF(
    'UPI transaction'[Customer Age] <= 25, "A1",
    IF(
        'UPI transaction'[Customer Age] <= 35,
        "A2",
        "A3"
    )
)

📈 Dashboard Features

Transaction Analysis
Monthly Transaction Amount (Line Chart)
Monthly Transaction Amount (Column Chart)

Balance Analysis
Monthly Remaining Balance (Line Chart)
Monthly Remaining Balance (Column Chart)

Matrix Analysis
Matrix visual showing:
Amount
Remaining Balance
Grouped by:
City
Currency

Interactive Filters
Dashboard includes 10 slicers for detailed analysis:
Bank Name Sent
Bank Name Received
City
Device Type
Gender
Merchant Name
Transaction Type
Age Group
Payment Mode
Purpose

Advanced Power BI Features

Sync Slicers across report pages
Bookmarks for navigation
Selection Pane for object management
Interactive cross-filtering
Responsive dashboard layout

📌 Key Insights
Analyze monthly transaction trends throughout the year.
Compare balances across different months.
Evaluate city-wise transaction performance.
Compare transaction amounts across multiple currencies.
Filter dashboards instantly using multiple business dimensions.
Understand customer behavior through age segmentation.

🛠️ Tools & Technologies
Microsoft Power BI
Power Query
DAX
Data Modeling
Excel
Data Profiling
Interactive Dashboard Design

🚀 Future Improvements
Add KPI Cards (Total Transactions, Total Amount, Average Transaction Value)
Include Year-over-Year (YoY) analysis
Implement dynamic tooltips





Your .pbix file
The Excel dataset (if it's shareable)
Screenshots of both dashboard pages
A short demo GIF or video (optional)

A well-organized repository like this will look professional to recruiters and can strengthen your Data Analyst portfolio.
