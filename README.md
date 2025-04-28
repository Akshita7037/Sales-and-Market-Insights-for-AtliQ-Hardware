📋Project Overview :

This project focuses on analyzing AtliQ Hardware's retail performance using a MySQL dataset and Power BI. The data set comprises five tables (market, product, date, customer, transaction) and was imported into Power BI using an ODBC connector. The project involves data cleaning, transformation, and measure calculation to derive actionable insights. Data preprocessing was performed using Power Query Editor to handle inconsistent or blank values, and DAX was used to calculate key measures such as Revenue, Profit Margin %, Profit Margin Contribution %, Revenue Contribution %, and Total Expenses. These measures were then used to create four comprehensive reports with visualizations to support strategic decision-making. The project structure is divided into four reports, each addressing specific aspects of sales, profitability, customer behavior, product demand, and performance comparisons, enabling AtliQ Hardware to optimize its retail operations.




🏆 Business Objectives: 

AtliQ Hardware faces challenges in optimizing its retail operations due to limited visibility into key performance metrics. The company lacks actionable insights into sales trends, profitability drivers, market and customer contributions, and product demand, hindering effective decision-making. Specifically, there is a need to identify high-performing markets, top customers, and in-demand products, while also understanding profit margin variations, expense trends, and performance against profit targets. This project aims to address these gaps by leveraging Power BI to analyze sales, profitability, and customer behavior, enabling AtliQ Hardware to make data-driven decisions to enhance business growth and operational efficiency.The primary objective of this project is to empower Atliq Hardware’s business teams with actionable sales and market insights through an interactive Power BI dashboard. By leveraging historical sales, market, and customer data stored in the MySQL database, the project aims to identify key revenue drivers, monitor sales performance across different markets, evaluate profitability trends, and uncover growth opportunities. The goal is to support data-driven decision-making by providing a centralized, easy-to-understand visual platform that highlights important KPIs, market behaviors, product performances, and customer contributions. Ultimately, this dashboard is designed to help Atliq Hardware optimize sales strategies, improve market positioning, and enhance overall business profitability.







⚙️ Implementation Methodology: 

1. Requirement Gathering
   
Defined KPIs: Revenue, Profit Margin %, Sales Volume, Top Markets/Customers/Products.


3. Data Acquisition
   
Source: MySQL (5 Tables: Transaction, Product, Customer, Date, Market).

Imported via ODBC Connector into Power BI.


5. Data Preparation & Transformation
   
Cleaned data using Power Query Editor.

Built a star schema with Transaction as Fact Table.

Fixed inconsistencies and ensured data quality.



7. Data Modeling & DAX Calculation
   
Created relationships between tables.

Built DAX Measures for Total Revenue, Profit Margin %, YoY Growth, etc.



9. Dashboard Design & Insight Generation
    
Interactive Power BI dashboard with slicers, filters, and tooltips.

Delivered actionable business insights to stakeholders.






📈 Key Insights & Findings:

1. Revenue and Market Performance Delhi NCR, Mumbai, and Ahmedabad generate over 80% of total revenue.
2. Bengaluru, Bhubaneshwar, and Surat are underperforming, needing strategic interventions.
3. Revenue peak was observed in early 2018 (₹42.52M); a sharp decline occurred in 2020 due to external factors like COVID-19.
4. Sales Volume Distribution Delhi NCR leads with 988K units sold, followed by Mumbai and Nagpur.
5. Cities with low volume and revenue (e.g., Bengaluru, Patna) require localized marketing and distribution improvements.
6. Customer & Product Analysis Electricalsara Store alone contributes ~42% of total revenue (₹413M), indicating high dependency.
7. One product (Blank) accounts for 48% of revenue, highlighting product concentration risk.
8. Top products in demand: Prod090, Prod239, and Prod237.
9. Profitability Insights Highest profit margins in Surat (4.86%), Patna (4.12%), and Bhubaneshwar (3.98%).
10. Loss-making markets like Bengaluru (-20.78%) and Kanpur (-0.49%) require urgent review.
11. Central Zone shows the best profit margin (3.3%) across all regions.






🛠 Technologies Used


1. Front-End

Technology: Power BI Desktop

Version: 2.141.1754.0 (64-bit)

Purpose: Dashboard development


2. Back-End

Technology: MySQL Database Server

Version: 8.0.41.0 Community Edition

Purpose: Data storage and management


3. Tools

Technology: ODBC Connector

Version: 8.0.33

Purpose: Data connection between MySQL and Power BI


4. Operating System

Technology: Microsoft Windows 11

Version: 10.0.26100

Purpose: System platform for development and testing


5. Editors

Technology: Power BI, MySQL Workbench

Version: Latest versions

Purpose: Data extraction, transformation, and visualization







📊 Dashboard Key Modules 

1. Revenue & Sales Performance

2. Market and Regional Insights

3. Customer and Product Profitability

4. Profit Margin Target Achievement

