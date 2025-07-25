# Coffee Sales Dashboard Project

## Overview

This project presents a comprehensive coffee sales dashboard designed to visualize key sales metrics, identify trends, and provide actionable business insights from a dataset of coffee sales, customer, and product information. The dashboard allows for interactive exploration of sales performance across different coffee types, geographical regions, and customer segments.


## Why This Project is Relevant

In the competitive retail landscape, understanding sales performance is paramount for strategic decision-making. A well-designed sales dashboard empowers businesses to:

Monitor Performance: Quickly track sales trends and identify deviations from targets.

Identify Opportunities: Pinpoint best-selling products, top-performing customer segments, and high-potential regions.

Optimize Strategies: Inform marketing campaigns, inventory management, and customer retention efforts based on data-driven insights.

Enhance Efficiency: Reduce time spent on manual reporting by providing an interactive, self-service analytical tool.


## Research Objectives

This dashboard aims to answer critical business questions, including:

What are the overall sales trends over time (yearly, monthly)?

Which coffee types (Arabica, Excelsa, Liberica, Robusta) are the most popular and contribute most to sales?

How do sales vary by roast type (Light, Medium, Dark) and size?

What is the geographical distribution of sales across different countries?

Who are the top-performing customers by sales volume?

How do loyalty card holders compare to non-loyalty card holders in terms of sales contribution?


## Methodology

The project involved extracting, cleaning, and integrating data from various CSV files to create a unified dataset suitable for dashboard visualization. The data was then loaded into a Business Intelligence (BI) tool (e.g., Power BI, Tableau, or Excel, depending on the implementation) to build interactive visualizations and reports.


## Data Sources and Features

The dashboard is built upon data extracted from the following CSV files, which originated from different tabs in a master Excel dataset:

orders.csv: Contains detailed information about each order, including Order ID, Order Date, Customer ID, Product ID, Quantity, Unit Price, and Sales. This is one of the primary data tabs.

customers.csv: Provides customer details such as Customer ID, Customer Name, Country, and Loyalty Card status. This is one of the primary data tabs.

products.csv: Includes product specifications like Product ID, Coffee Type, Roast Type, Size, Unit Price, and Profit. This is one of the primary data tabs.


## Data Pre-processing

The data pre-processing steps involved:

Loading Data: Importing the individual CSV files into the chosen BI tool.

Data Cleaning: Ensuring data consistency and handling any potential formatting issues (e.g., date formats, numerical values).

Data Integration: Establishing relationships between tables (e.g., orders linked to customers and products via their respective IDs) to enable cross-table analysis.

Calculations/Aggregations: Creating necessary measures and calculated columns (e.g., total sales, average sales) and aggregating data to various levels of granularity (e.g., monthly sales, sales by coffee type).


## Data Processing/Analysis/Methods Used

The primary method used is Data Visualization and Interactive Reporting within a BI environment. This involves:

Time Series Analysis: Visualizing sales trends over time using line charts.

Categorical Analysis: Using bar charts and pie charts to compare sales across different coffee types, roast types, sizes, and countries.

Ranking: Identifying top customers by sales.

Filtering and Slicing: Implementing interactive filters to allow users to drill down into specific periods, coffee types, or customer segments.


## Technologies Used

Microsoft Excel: Used for the original dataset files and potentially for the dashboard itself if implemented purely in Excel.

MS Excel: The primary tool used for creating the interactive dashboard, data modeling, and visualizations.


## Key Findings 


While the live dashboard provides dynamic insights, here are some examples of the types of findings one can derive:

Overall Sales Performance: The dashboard clearly shows annual and monthly sales trends, highlighting periods of high and low performance.

Top Coffee Types: Analysis reveals that [e.g., Arabica] consistently leads in sales, providing insights for inventory and marketing focus.

Geographical Distribution: The majority of sales are concentrated in [e.g., the United States], followed by [e.g., Ireland] and [e.g., United Kingdom].

Customer Loyalty Impact: Customers with loyalty cards contribute significantly more to overall sales, emphasizing the value of loyalty programs.

Seasonal Trends: Certain months or quarters might show consistent peaks or troughs in sales, indicating seasonal demand patterns.


## Recommendations

Based on the insights gained from the dashboard, here are some potential recommendations for the business:

Focus on Top Performers: Prioritize marketing and inventory for the highest-selling coffee types and top customer segments.

Target Underperforming Regions: Investigate reasons for lower sales in certain countries and develop targeted strategies.

Enhance Loyalty Programs: Leverage the higher sales contribution from loyalty card holders by expanding loyalty benefits or running exclusive promotions.

Optimize Inventory: Use sales trends to better forecast demand and optimize stock levels, especially for seasonal peaks.

Personalized Marketing: Utilize customer segmentation insights to create more targeted marketing campaigns.
