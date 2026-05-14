# Adidas-sales
Project Overview--

The Adidas Sales Analysis Dashboard is a Power BI project developed to analyze and visualize sales performance data across multiple business dimensions such as products, regions, retailers, and sales methods. The dashboard transforms raw sales data into interactive reports and meaningful insights that help management monitor business performance and make strategic decisions.
The project focuses on identifying sales trends, profitability, product demand, and operational efficiency using data visualization and DAX measures in Power BI.

Project Objective--

To analyze Adidas sales and profit performance using interactive dashboards.
To identify top-performing products, retailers, and regions.
To monitor key business KPIs such as total sales, profit, units sold, and operating margin.
To provide actionable business insights for improving profitability and sales growth.
To support data-driven decision-making through visual analytics.

Scope of Work--

Import and clean Adidas sales dataset in Power BI.
Perform data transformation using Power Query Editor.
Create calculated measures and KPIs using DAX.
Design an interactive single-page dashboard with charts, slicers, and KPI cards.
Analyze sales trends, product performance, and sales methods.
Generate business insights and recommendations based on dashboard analysis.
Develop a professional and user-friendly dashboard layout for stakeholders.

Data Source--

The project uses the Adidas Sales dataset imported from CSV format into Power BI Desktop.
Data Architecture Flow
Raw Excel Dataset
Power Query Data Cleaning
Data Modeling & DAX Measures
Power BI Visualizations
Interactive Dashboard & Insights
The dataset acts as a centralized sales table used for analysis and dashboard reporting.

Implementation Steps
Data Import

Imported the Adidas sales dataset into Power BI Desktop from Excel  source.

DAX Measure Creation
Created calculated measures for:

Total Sale  — Total Sales 1 = SUM('Data Sales Adidas'[Total Sales])

Total Profit – Total Profit = SUM('Data Sales Adidas'[Operating Profit])

Margin % –  Margin % = [Total Profit]/[Total Sales 1]

Average Price per Unit - Avg Price Per Unit = AVERAGE('Data Sales Adidas'[Price per Unit])

Dashboard Development

Designed dashboard visuals including:
Two pages -Sales Overview ,Product and Geography Analysis

KPI Cards
Line Chart – Analyze sales  trends over time. 

Funnel Chart – Analyze units sold by product category.

Donut Chart — Analyze profit contribution by sales method. 

Table Visual – Display detailed product-wise sales analysis. 

Slicers→ Operating Margin

Line chart - Total Profit by Product 

Units Sold by Region (Tree Map)

Column - Sales by Sales Method

Bar  chart -  Sales by State

These filters allow users to dynamically analyze data based on business requirements.

Tools & Technologies Used--
Power BI Desktop,
Power Query,
DAX ,
Microsoft Excel.

Business Insights--

Men’s Street Footwear generated high sales volume.
Certain regions contributed higher profits compared to others.
Online sales methods showed strong profit contribution.
Products with higher operating margins improved profitability.
Sales trends indicate fluctuating monthly performance.

Dashboard pages-

<img width="928" height="497" alt="adidas sales1" src="https://github.com/user-attachments/assets/dcd87609-4c2b-4b63-8f32-afdb073937b0" />
<img width="928" height="497" alt="adidas product wise" src="https://github.com/user-attachments/assets/1b14bead-f552-4f85-98df-2b4e691a7797" />


