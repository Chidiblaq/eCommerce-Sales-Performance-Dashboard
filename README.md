# eCommerce Sales Performance Dashboard

## Overview  
This project analyzes the sales KPI performance for a US-based eCommerce company. The goal is to create a comprehensive sales performance dashboard displaying Year-to-Date (YTD) Sales, YTD Profit, YTD Quantity (sold units), and the YTD Profit Margin. The project also generates insights into various sales scenarios using different visualizations.

## Business Case  
In today's competitive eCommerce landscape, it is crucial for businesses to have a clear understanding of their sales performance to make informed strategic decisions. The eCommerce company in this project needs to:  
- Track Performance: Monitor YTD Sales, YTD Profit, YTD Quantity, and YTD Profit Margin to ensure they are meeting their targets.  
- Identify Trends: Understand monthly sales trends and YoY growth to adjust marketing and sales strategies accordingly.  
- Optimize Product Portfolio: Determine which product categories are performing well and which are underperforming to manage inventory and marketing efforts effectively.  
- Geographic Insights: Analyze sales performance across different states and regions to identify high and low-performing areas.  
- Improve Shipping Strategies: Evaluate the effectiveness of different shipping types to optimize logistics and reduce costs.  
- Strategic Decision Making: Provide insights to the management team to help them make data-driven decisions that can drive growth and improve profitability.  
- A well-designed sales performance dashboard can provide these insights in a clear and actionable manner, helping the company to stay competitive and grow in the market.  

## Problem Statement  
The eCommerce company requires a dashboard that provides:  
1. A KPI Banner showing YTD Sales, YTD Profit, YTD Quantity (sold units), and the YTD Profit Margin.  
2. Year-over-Year (YoY) growth for each KPI, along with YTD sparklines to understand monthly trends.  
3. YTD Sales, Previous Year-to-Date (PYTD) Sales, and YoY Sales growth for different product categories, including trend icons for each category. Similar insights for Profit and Profit Margin.  
4. YTD Sales performance for each state, and similar insights for Profit and Profit Margin.  
5. Identification of the top 5 and bottom 5 products by Sales, Profit, and Profit Margin.  
6. YTD Sales by region to identify the best and worst performing regions, with similar insights for Profit and Profit Margin.  
7. YTD Sales by shipping type to determine the best shipping type, with similar insights for Profit and Profit Margin.

## Project Structure  
### Data Collection and Preparation  
- Data Source: Kaggle  
- Data Storage: Microsoft SQL Server  
- Data Cleaning and Transformation: Microsoft SQL Server, Power Query in Power BI

### Data Modeling  
- Fact Table: Contains sales data  
- Dimension Tables: Date and US States Longitude and Latitude  
- Relationships: Established between fact and dimension tables

### DAX Functions  
- Time Intelligence: TOTALYTD, SAMEPERIODLASTYEAR  
- Conditional Formatting: Applied for better visualization

### Visualizations  
- Card: Display KPIs like YTD Sales, YTD Profit, YTD Quantity, YTD Profit Margin.  
- Area Chart: Show trends over time  
- Matrix: Detailed comparisons  
- Map: Geographic sales performance  
- Bar Chart: Ranking of products and categories  
- Donut Chart: Distribution analysis
  
## Tools Used  
- Microsoft Power BI: Dashboard creation and visualization  
- Microsoft SQL Server: Data storage and querying  
- Microsoft Excel: Additional data manipulation  
- Power Query: Data transformation within Power BI
  
## Process
- Data Import: Data was downloaded from Kaggle and imported into SQL Server.  
- Data Cleaning: Initial data cleaning and querying were done in SQL Server.  
- Data Transformation: Further transformation was performed in Power Query.  
- Data Modeling: Relationships were established between the fact and dimension tables.  
- DAX Functions: Created to calculate KPIs and apply conditional formatting.  
- Visualization: Various charts were created to analyze and present the data.  

## Insights Generated  
- KPI Banner: Displays YTD Sales, YTD Profit, YTD Quantity, and YTD Profit Margin.  
- YoY Growth: Year-over-Year growth for each KPI with monthly trends.  
- Category Analysis: YTD Sales, PYTD Sales, YoY Sales growth, Profit, and Profit Margin for different product categories.  
- State Performance: Sales performance for each state, with insights for Profit and Profit Margin.  
- Product Ranking: Top 5 and Bottom 5 products by Sales, Profit, and Profit Margin.  
- Regional Analysis: Best and worst performing regions for Sales, Profit, and Profit Margin.  
- Shipping Analysis: Best shipping type for Sales, Profit, and Profit Margin.

## Conclusion  
This project successfully created a detailed sales performance dashboard for a US-based eCommerce company. The dashboard provides valuable insights into sales KPIs, helping the company make data-driven decisions to improve their performance.

## Getting Started  
### Prerequisites  
- Microsoft Power BI  
- Microsoft SQL Server  
- Microsoft Excel  

### Installation  
- Clone the repository: git clone https://github.com/Chidiblaq/eCommerce-Sales-Performance-Dashboard.git  
- Open the Power BI file in Microsoft Power BI.  

### Usage  
- Load the data into SQL Server.  
- Transform the data using Power Query in Power BI.  
- Analyze the data using the provided visualizations.  
