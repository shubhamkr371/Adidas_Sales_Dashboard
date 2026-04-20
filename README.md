📘 Power bi  Data Analysis Project Report

1. INTRODUCTION
· In today’s highly competitive global sportswear market, Adidas is a leading brand operating across multiple sales channels and regions.
· Analyzing large volumes of sales data is essential to understand market demand, regional performance, and customer purchasing behavior.
· This project presents a structured data analysis using power bi to evaluate and visualize Adidas sales data effectively.
· The study is supported by an interactive power bi dashboard that provides a clear overview of business performance and trends.
· The dashboard highlights key performance indicators such as:
Total Sales
Operating Profit
Units Sold
Sales by Region
Sales by Method (Online, Outlet, In-store)
Retailer-wise Performance
Product Category-wise Sales
· Through visual analytics and filtering options, the dashboard enables stakeholders to compare performance across regions, identify top-performing retailers, and support data-driven decision-making.


2. SOURCE OF DATASET
The dataset used in this project is an Adidas sales dataset stored in a structured tabular format (CSV/Excel). It contains detailed information related to product sales, regions, retailers, and sales performance.
Dataset attributes include:
Invoice Date
Region
State
City
Retailer
Sales Method (Online, Outlet, In-store)
Product Category
Product Type
Units Sold
Price per Unit
Total Sales
Operating Profit
Operating Margin
The dataset is well-structured and suitable for data analysis and visualization, enabling meaningful insights into regional sales trends, retailer performance, and product demand.
It was imported directly into Microsoft Power bi and used to build an interactive dashboard for effective business analysis and decision-making.

 

3. DATASET PREPROCESSING
Dataset preprocessing was carried out using Power Query Editor in Microsoft Power bi to ensure data accuracy, consistency, and readiness for analysis.
3.1 Data Cleaning
Removed null and blank records from key fields such as Sales, Units Sold, Region, and Retailer.
Corrected and validated data types (numeric values for sales and profit, text for categories).
Removed or corrected invalid and unrealistic values (negative sales, zero units sold).
Standardized categorical values such as Region names, Sales Methods, Product Categories, and Retailers for consistency.
3.2 Data Processing
Created calculated columns to derive Total Sales, Operating Profit, and Operating Margin.
Extracted Month, Quarter, and Year from Invoice Date to support time-based analysis.
Grouped and aggregated data for region-wise, product-wise, and retailer-wise performance evaluation.
3.3 Data Modeling
Created a Date (Calendar) table to enable accurate time intelligence analysis
Established One-to-Many relationships between the Date table and the Sales table.
Applied a Star Schema model to improve performance, simplify filtering, and enhance dashboard interactivity.


4. ANALYSIS ON DATASET

Objective 1: Overall Sales Performance
i. General Description
This analysis provides a high-level overview of Adidas’ overall sales performance, helping to understand the business impact in terms of revenue, profitability, and sales volume.
ii. Specific Requirements
Total Sales
Total Units Sold
Operating Profit
Sales contribution across regions
iii. Analysis Results
Total Sales: 900M
Total Units Sold: 2M
Operating Profit: 332M
Top Performing Region: West (highest sales contribution)
Lowest Performing Region: Midwest
iv. Visualization
KPI Cards displayed at the top of the dashboard highlight Total Sales, Units Sold, and Operating Profit for quick performance assessment.




Objective 2: Product-Wise Sales Analysis
General Description
This analysis identifies which Adidas product categories and types contribute the most to overall sales and units sold.
Analysis Results
Men’s Footwear and Men’s Apparel contribute the highest share of total sales.
Women’s Apparel and Footwear show steady but comparatively lower contribution.
Niche product categories contribute minimal sales volume.
Visualization
Table visualization displaying product categories with sales and units sold indicators.

Objective 3: Monthly Sales Trend Analysis
Description
This analysis examines monthly sales trends, comparing performance across different time periods to identify seasonal patterns.
Results
Clear seasonal variation observed in sales performance.
Certain months show peak sales activity, indicating high consumer demand during specific periods.

Visualization
Line chart showing Monthly Sales Trend (Month-wise performance comparison).

Objective 4: Sales Method & Retailer Performance
Description
Evaluates the impact of sales methods and retailer channels on overall sales and profitability.
Results
Online sales contribute the highest revenue among all sales methods.
In-store and outlet sales show moderate but consistent performance.
Key retailers such as West Gear and Foot Locker outperform others in total sales.
Visualizations
Bar chart – Sales by Sales Method
Donut chart – Sales contribution by Retailer

Objective 5: Regional Sales Analysis
Results
West region contributes the highest percentage of total sales.
Northeast and Southeast show balanced performance.
Midwest records the lowest sales contribution.
Visualization
Donut chart showing Region-wise Sales Distribution.


Objective 6: Geographical Performance Analysis
Description
Displays state-wise and city-wise sales distribution to identify high-performing and low-performing locations.
Results
Certain states and cities demonstrate significantly higher sales concentration.
Geographic insights help in identifying potential markets for expansion.
Visualization
Map visualization showing Sales by Region.


5. CONCLUSION
This project presents an interactive Adidas Sales Analysis Dashboard developed using Power bi to evaluate and visualize sales performance effectively. The dataset was cleaned, processed, and modeled to ensure accuracy, consistency, and reliable analysis. Key performance indicators were created to summarize total sales, units sold, operating profit, and regional contributions.
The dashboard highlights important patterns such as strong sales performance in men’s footwear and apparel, higher revenue contribution from online sales channels, and noticeable differences in regional and retailer-wise performance. Monthly trend analysis reveals seasonal fluctuations in sales, helping identify peak demand periods. The geographical map visualization assists in spotting high-performing states and cities, enabling better market targeting and strategic planning.
Overall, this project demonstrates how Microsoft Power bi dashboards can transform raw sales data into actionable business insights, supporting informed decision-making in sales optimization, inventory planning, and market expansion strategies.


6. FUTURE SCOPE
Integration of real-time sales data from online platforms and retail systems for up-to-date performance monitoring.
Predictive analytics models to forecast future sales trends, demand patterns, and revenue growth.
Advanced geographical analysis to identify emerging markets and optimize regional expansion strategies.
Machine learning–based customer and product insights to improve personalization and recommendation strategies.
Decision-support dashboards for management to enhance strategic planning, inventory control, and marketing effectiveness.
