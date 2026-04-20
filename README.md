📘 Power BI Data Analysis Project Report
1. INTRODUCTION

In today’s competitive global sportswear industry, Adidas stands as a major brand operating across various regions and sales channels. Analyzing large-scale sales data is essential to understand customer behavior, regional demand, and overall market trends.

This project focuses on performing structured data analysis using Power BI to evaluate Adidas sales performance. An interactive Power BI dashboard has been developed to present clear insights into business operations.

The dashboard highlights key performance indicators such as:

Total Sales
Operating Profit
Units Sold
Regional Sales Distribution
Sales by Method (Online, Outlet, In-store)
Retailer Performance
Product Category Sales

Through interactive visuals and filters, stakeholders can easily compare performance, identify top retailers, and make data-driven decisions.

2. SOURCE OF DATASET

The dataset used in this project is an Adidas sales dataset stored in structured formats like CSV or Excel. It contains detailed information about products, regions, retailers, and sales metrics.

Key attributes include:

Invoice Date
Region, State, City
Retailer
Sales Method (Online, Outlet, In-store)
Product Category & Type
Units Sold
Price per Unit
Total Sales
Operating Profit & Margin

The dataset is well-organized and suitable for analysis. It was imported into Microsoft Power BI to create an interactive dashboard for better visualization and decision-making.

3. DATASET PREPROCESSING
3.1 Data Cleaning
Removed null and blank values from important fields like Sales, Units Sold, Region, and Retailer
Ensured correct data types (numeric and categorical)
Eliminated invalid data such as negative sales or zero units
Standardized category names (Region, Sales Method, Product Categories, Retailers)
3.2 Data Processing
Created calculated columns for Total Sales, Operating Profit, and Margin
Extracted Month, Quarter, and Year from Invoice Date
Aggregated data for region-wise, product-wise, and retailer-wise analysis
3.3 Data Modeling
Built a Date (Calendar) table for time-based analysis
Established relationships between tables (One-to-Many)
Applied Star Schema for better performance and simplified analysis
4. DATA ANALYSIS
Objective 1: Overall Sales Performance

This analysis gives a summary of Adidas’ business performance in terms of revenue, profit, and sales volume.

Results:

Total Sales: 900M
Units Sold: 2M
Operating Profit: 332M
Highest Sales Region: West
Lowest Sales Region: Midwest

Visualization: KPI cards displaying key metrics for quick insights

Objective 2: Product-Wise Sales Analysis

This analysis identifies top-performing product categories.

Results:

Men’s Footwear and Apparel contribute the most
Women’s products show moderate performance
Other categories have lower contribution

Visualization: Table showing category-wise sales and units

Objective 3: Monthly Sales Trend

This evaluates sales patterns over time.

Results:

Seasonal trends are clearly visible
Certain months show peak demand

Visualization: Line chart showing monthly performance

Objective 4: Sales Method & Retailer Analysis

This examines how sales channels and retailers impact performance.

Results:

Online sales generate the highest revenue
In-store and outlet sales are stable
Retailers like West Gear and Foot Locker perform best

Visualization:

Bar chart (Sales by Method)
Donut chart (Retailer contribution)
Objective 5: Regional Sales Analysis

Results:

West region leads in sales
Northeast and Southeast perform steadily
Midwest shows lowest contribution

Visualization: Donut chart showing regional distribution

Objective 6: Geographical Analysis

This focuses on location-based performance.

Results:

Certain cities and states show higher sales
Helps identify expansion opportunities

Visualization: Map displaying sales distribution

5. CONCLUSION

This project demonstrates how an interactive Power BI dashboard can effectively analyze and visualize Adidas sales data. The dataset was cleaned, processed, and modeled to ensure accurate insights.

Key findings include:

Strong performance in men’s product categories
Higher revenue from online sales
Noticeable regional differences in performance
Seasonal trends in monthly sales

Overall, the dashboard converts raw data into meaningful insights, helping businesses improve sales strategies, inventory planning, and market expansion.

6. FUTURE SCOPE
Integration of real-time data for live monitoring
Use of predictive analytics for future sales forecasting
Advanced geographical insights for expansion planning
Machine learning for customer behavior analysis
Enhanced decision-support dashboards for management
