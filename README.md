Project Overview
This project delivers an end-to-end Sales, Market, and Profitability Insights Dashboard for Atliq Hardware.
The aim is to empower business stakeholders with data-driven insights into revenue performance, customer segmentation, product analysis, and market opportunities across India.
The solution utilizes MySQL as the data source and Power BI for data modeling, visualization, and reporting.


🏆 Business Objectives
Improve profitability through cost optimization and pricing strategy refinement.

Identify high-performing and under-performing markets.

Optimize sales volume distribution and customer engagement strategies.

Reduce revenue concentration risks by diversifying product and customer bases.

Recover from revenue decline post-2019 by focusing on high-potential and high-margin markets.



⚙️ Implementation Methodology
Requirement Gathering

Defined KPIs: Revenue, Profit Margin %, Sales Volume, Top Markets/Customers/Products.

Data Acquisition

Source: MySQL (5 Tables: Transaction, Product, Customer, Date, Market).

Imported via ODBC Connector into Power BI.

Data Preparation & Transformation

Cleaned data using Power Query Editor.

Built a star schema with Transaction as Fact Table.

Fixed inconsistencies and ensured data quality.

Data Modeling & DAX Calculation

Created relationships between tables.

Built DAX Measures for Total Revenue, Profit Margin %, YoY Growth, etc.

Dashboard Design & Insight Generation

Interactive Power BI dashboard with slicers, filters, and tooltips.

Delivered actionable business insights to stakeholders.



📈 Key Insights & Findings
Revenue and Market Performance
Delhi NCR, Mumbai, and Ahmedabad generate over 80% of total revenue.

Bengaluru, Bhubaneshwar, and Surat are underperforming, needing strategic interventions.

Revenue peak was observed in early 2018 (₹42.52M); a sharp decline occurred in 2020 due to external factors like COVID-19.

Sales Volume Distribution
Delhi NCR leads with 988K units sold, followed by Mumbai and Nagpur.

Cities with low volume and revenue (e.g., Bengaluru, Patna) require localized marketing and distribution improvements.

Customer & Product Analysis
Electricalsara Store alone contributes ~42% of total revenue (₹413M), indicating high dependency.

One product (Blank) accounts for 48% of revenue, highlighting product concentration risk.

Top products in demand: Prod090, Prod239, and Prod237.

Profitability Insights
Highest profit margins in Surat (4.86%), Patna (4.12%), and Bhubaneshwar (3.98%).

Loss-making markets like Bengaluru (-20.78%) and Kanpur (-0.49%) require urgent review.

Central Zone shows the best profit margin (3.3%) across all regions.



🛠 Technologies Used
Front-End:

Technology: Power BI Desktop

Version: 2.141.1754.0 (64-bit)

Purpose: Dashboard development

Back-End:

Technology: MySQL Database Server

Version: 8.0.41.0 Community Edition

Purpose: Data storage and management

Tools:

Technology: ODBC Connector

Version: 8.0.33

Purpose: Data connection between MySQL and Power BI

Operating System:

Technology: Microsoft Windows 11

Version: 10.0.26100

Purpose: System platform for development and testing

Editors:

Technology: Power BI, MySQL Workbench

Version: Latest versions

Purpose: Data extraction, transformation, and visualization



📊 Dashboard Key Modules
Revenue & Sales Performance

Market and Regional Insights

Customer and Product Profitability

Profit Margin Target Achievement
