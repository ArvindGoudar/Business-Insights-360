# AtliQ Hardware-Business Insights 360

## Company Overview

AtliQ Hardware is a global electronics company specializing in computers, peripherals, and accessories. The company offers a wide range of products, including desktops, laptops, keyboards, mice, monitors, printers, and storage devices.

With a strong global presence in regions like APAC, North America, Latin America, and the EU, AtliQ distributes its products through retailers, direct stores, and distributors. Sales channels include brick-and-mortar stores (e.g., Croma, Best Buy) and e-commerce platforms (e.g., Amazon, Flipkart).

## Objective of the Project

Recently, AtliQ faced unexpected losses in its operations due to relying on outdated Excel-based analytics and intuition-based decisions rather than data-driven insights. In contrast, competitors leverage advanced analytics for strategic decision-making.

The goal of this project is to develop an intuitive and interactive dashboard that provides actionable insights for key business functions, including finance, sales, marketing, and supply chain. Additionally, it will feature an executive and key performers view to enhance transparency, data accessibility, and strategic decision-making.

*Key Focus Areas*
- ✅ Sales Performance Analysis – Track revenue trends across different regions and sales channels.
- ✅ Market Insights – Identify gaps and opportunities through competitor analysis.
- ✅ Operational Efficiency – Optimize supply chain and inventory management using data-driven strategies.

#### LIVE DASHBOARD LINK  
🔗 [Click here to view the dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjE4ZWI2MGQtOThhMy00NWQyLWE5ZGYtODQzMDMzYzYxZDYxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)  

## Available Data Sources

AtliQ Hardware has provided two SQL databases and three Excel files for analysis.

### Excel Files 
- Operating Expenses – Contains company-wide expense data.
- Targets (FY 2022 only) – Sales targets for the fiscal year 2022.
- Market Share (Personal Computer Division) – Limited to PC segment analysis.

### SQL Databases 

*Database: gdb041*
*Fact Tables*
- fact_forecast_monthly – Monthly sales forecasts.
- fact_sales_monthly – Actual monthly sales data.

*Dimension Tables*

- dim_customer – Customer details.
- dim_market – Market segmentation.
- dim_product – Product information.

*Database: gdb056*
*Financial & Cost Data Tables*

- freight_cost – Logistics and shipping costs.
- gross_price – Product pricing before discounts.
- manufacturing_cost – Production expenses.
- post_invoice_deductions – Discounts applied after invoicing.
- pre_invoice_deductions – Discounts and adjustments before invoicing.

*Timeframe & Fiscal Year*

AtliQ’s fiscal year runs from September to August.
The dataset includes actual sales data from September 1, 2017, to December 31, 2021.

## 𝗧𝗢𝗢𝗟𝗦 𝗜 𝗨𝗦𝗘𝗗
- SQL
- PowerBi Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)

## Importing data into Power BI

As the database is MySQL in this project, we need to import the datasets from the MySQL database to Power BI by providing the Database access credential.

## Key Learnings and Skills Gained


- Understanding Business Metrics: Gained deeper insights into key business metrics and their impact on company performance, strengthening the ability to assess business outcomes.

- Power BI Dashboards: Designed user-friendly and insightful Power BI dashboards that effectively visualize complex data for decision-makers.

- Advanced DAX Techniques: Developed proficiency in creating calculated columns and measures using DAX language, providing customized and dynamic insights.

- Data Integration: Successfully connected and combined data from diverse sources like MySQL and Excel, offering a comprehensive view of business operations.

- Data Modeling: Improved data structuring and relationships, enabling more accurate analysis and reporting across multiple business functions.

- Storytelling with Bookmarks: Utilized Power BI bookmarks to switch between visuals, enhancing storytelling and the clarity of data presentations.

- Dynamic Visuals with Conditional Formatting: Applied conditional formatting to visuals, using custom icons and background colors to emphasize important data points.

- Page Navigation and User Experience: Integrated seamless page navigation with buttons and tooltips to provide an interactive and user-friendly experience for stakeholders.

- Real-Time Data Refresh: Set up auto-refresh capabilities using Power BI services and a personal gateway, ensuring that reports always present up-to-date information.

- Collaboration and Reporting: Gained expertise in publishing reports, managing access permissions, and collaborating within Power BI services, ensuring efficient team workflows and secure data sharing.
