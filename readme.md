📊 Retail Sales Analysis - Power BI Project

📝 Overview
This project demonstrates the end-to-end process of building a Retail Sales Analysis Dashboard using Power BI. The dashboard delivers comprehensive insights into retail performance, including revenue trends, profit margins, regional sales distribution, and product-wise comparisons.

📌 Project Objectives
Clean and prepare raw sales data for analysis.

Perform essential data transformation tasks such as handling null values and removing duplicates.

Engineer new metrics like Profit Margin to enhance analysis depth.

Develop an interactive and user-friendly dashboard to help stakeholders make data-driven decisions.

🔧 Data Preparation Steps
1. Remove Unnecessary Columns
The column sales_rep was identified as non-essential to this analysis and was removed to streamline the dataset.

2. Handle Null Values
Rows containing null or missing values were removed to maintain data integrity and prevent errors during analysis.

3. Remove Duplicate Entries
Duplicate records were identified and eliminated to ensure the accuracy of the aggregated metrics and visuals.

4. Data Type Conversions
Data types were standardized and optimized:

Date columns (e.g., order_date) were converted to Date/Time format.

Numeric columns like revenue, cost, and profit were converted to Decimal Number.

Categorical data such as product and region were set as Text or Categorical types to enable filtering and slicing.

5.Feature Engineering – New Calculated Columns:

A new column Profit Margin was created using the formula:

Profit Margin
=
Profit
Revenue
Profit Margin= 
Revenue
Profit
​

This measure helps in understanding the profitability of each product or region more effectively.

📈 Dashboard Highlights
The final Power BI dashboard includes the following visuals and KPIs:

Total Revenue KPI: Clearly displays total revenue (25.92M) across all regions and products.

Revenue by Year: A line chart showing a consistent growth trend from 2023 to 2024.

Average Units Sold: Gauge showing the average units sold (10.22).

Revenue & Profit by Region: Clustered column chart comparing revenue and profit across regions: Europe, South America, Asia, and North America.

Revenue by Product: Donut chart breaking down product-wise revenue share.

Price vs. Cost Analysis: Clustered bar chart showing the cost and selling price for each product type.

Interactive Filters: Users can filter data using slicers for:

Product Type

Region

Date Range

🛠️ Tools Used
Power BI Desktop

Power Query (for data cleaning and transformation)

DAX (Data Analysis Expressions) for calculated columns and measures


🚀 Conclusion
This Power BI project highlights how raw retail sales data can be transformed into an interactive and insightful business intelligence dashboard. The analysis empowers businesses to:

Understand regional and product-wise performance.

Monitor revenue and profitability trends.

Make informed decisions backed by visual data storytelling.