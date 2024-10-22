# AtliQ Business Insights 360
## Project Overview

AltiQ Hardware is a fast-growing company that sells computers and accessories around the world through retailers, direct sales, and distributors.

However, after opening a store in America, the company faced unexpected losses. These issues were discovered through surveys and some basic analysis in Excel. With competitors using strong analytics, AltiQ Hardware realized it needed to improve its own data analysis skills to stay competitive.

To help make better decisions, the company decided to use Power BI for analytics. This project will give insights into finance, sales, marketing, and supply chain, helping everyone make informed choices.

I contributed to this project by taking the Codebasics Power BI Course.


Here is my report link - https://app.powerbi.com/view?r=eyJrIjoiNGI0MjFkMzEtMzZhYi00YzMwLThkZDYtMmNhODJmZTE4OGU1IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

## Datasets:
Before starting the analysis, it's important to understand the datasets well.

**Dimension table:** Static data like customer and product details.

**Fact table:** Transaction data.

gdb041:
* dim_customer
* dim_market
* dim_product
* fact_forecast_monthly - This table helps predict customer needs ahead of time, leading to higher customer satisfaction and lower storage costs in warehouses.
* fact_sales_monthly - This table is similar to the fact_forecast_monthly table, but the last column shows the actual sold quantity instead of the forecasted value.

gdb056:
* freight_cost
* gross_price
* manufacturing_cost
* Pre_invoice_dedutions
* Post_invoice_deductions

### Importing Data and Data Modeling:


Data was imported from MySQL into Power BI, and we created a data model after cleaning and transforming the data. But why is data modeling so important for analysis?

The work of a data analyst can be broken down into four steps:

✅ Data Extraction
✅ Data Cleaning
✅ Data Modeling
✅ Data Analysis

You can’t skip the third step if you want to successfully reach the analysis stage. Data modeling is crucial because it forms the foundation for reports. All visuals are built on the data model, and poor modeling can lead to performance issues in reports.

In this project, we used the Snowflake schema for data modeling.

![data model](https://github.com/HritikSundriyal/Business-Insight-360/blob/main/DATA%20MODEL.png)


### Home Page: A landing page with buttons to navigate to different sections of the site.

![home page](https://github.com/HritikSundriyal/Business-Insight-360/blob/main/HOME%20Page.png)


### Finance Page: This focuses on enhancing financial planning, budgeting, and cost control. It includes Profit and Loss statements, as well as insights on the top and bottom products and customers by net sales, among other metrics.

![finance page](https://github.com/HritikSundriyal/Business-Insight-360/blob/main/FINANCE%20Page.png)


### Sales Page: This aims to boost sales revenue and market share. It highlights customer performance through metrics like Net Sales, Gross Margin, Gross Margin %, and more.

![sales page](https://github.com/HritikSundriyal/Business-Insight-360/blob/main/SALES%20page.png)



### Marketing Page: This aims to enhance brand visibility and customer engagement. It offers insights into Segment Performance using metrics like Gross Margin % and Net Profit %, among others.

![marketing page](https://github.com/HritikSundriyal/Business-Insight-360/blob/main/MARKETING%20Page.png)


### Supply Chain Page: This aims to optimize inventory management and strengthen supplier relationships for cost savings. It includes metrics like Forecast Accuracy, Net Error, and more.

![supply chain](https://github.com/HritikSundriyal/Business-Insight-360/blob/main/SUPPLY%20CHAIN%20Page.png)


### Executive Page: This provides an overview of the organization’s performance for top management. It includes metrics such as Net Sales, Gross Margin %, Net Profit %, Revenue Contribution by channel, and insights on the Top 5 Customers and Products, as well as Sub Region performance, among others.

![executive page](https://github.com/HritikSundriyal/Business-Insight-360/blob/main/EXECUTIVE%20Page.png)

### Tools Used:
- SQL 
- Power BI Desktop 
- DAX language 
- DAX studio  

## Skills Learned:
During the Codebasics Bootcamp course and this project, I learned:

- Power BI fundamentals
- Calculated columns and DAX measures
- Data modeling and cleaning
- Bookmarks and conditional formatting
- Custom tooltip usage and dynamic title creation, among other skills.

### Here are some business terms I learned::

- Gross Margin 
- Gross Margin %
- Gross Sales
- Gross Sales %
- Pre-invoice deductions
- Post-invoice deductions
- Net sales
- Net Invoice Sales
- Net Profit
- Net Profit %
- COGS (cost of goods sold)
- YTG (year to go)
- YTD (year to date)
- Direct
- Retailer
- Consumer
- Distributors.
- Key Performance Indicators (KPIs)
- Profit and Loss (P&L) statements
- Market Share
- Forecast Accuracy
- Supply Chain Management

## Conclusion :
This report supports decision-making by answering various "why" questions across different scenarios. It acts as a tool for extracting insights and guiding actions, with the ultimate goal of boosting AltiQ's profitability through data-driven decisions.




