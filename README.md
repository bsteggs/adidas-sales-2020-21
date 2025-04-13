# Adidas U.S. Sales Dashboard (Excel)

An interactive business intelligence dashboard built in Microsoft Excel to analyze U.S. Adidas sales data. This project leverages Power Pivot, Power Query, and DAX to deliver dynamic insights on product performance, retail channel efficiency, and YoY growth across regions.

# Overview

This Excel-based dashboard allows users to explore:

- Year-over-Year (YoY) revenue growth and profit performance
- Retailer rankings based on total sales and operating margin
- Sales distribution by channel (Online, Outlet, In-Store)
- Product-level profitability and margin insights
- Geographic sales trends by region and U.S. state

The dashboard supports interactive filtering through slicers and timeline controls, with metrics dynamically updated via CUBEVALUE and PivotTable integration.

# Data Model

The dataset is structured in a star schema using:

- **Fact Table**: `Fact_Sales`  
- **Dimension Tables**: `Dim_Product`, `Dim_Retailer`, `Dim_Date`

Modeling and calculations were performed using **Power Pivot**, with DAX measures used to calculate Total Sales, Operating Profit, Average Order Value, and YoY change metrics.

# Tools & Skills Used

- Microsoft Excel  
- Power Pivot  
- Power Query  
- DAX  
- PivotTables & PivotCharts  
- CUBEVALUE & CUBEMEMBER  
- Timeline Slicers  
- Filled Map Visuals

# Key Metrics

- **Total Sales**  
- **YoY Sales Increase ($ and %)**  
- **Operating Profit**  
- **Gross Profit Margin**  
- **Top 3 Retailers by Sales**  
- **Sales by Region, Channel, and Product**

# Dataset Source

The sales dataset was sourced from [Kaggle](https://www.kaggle.com/datasets), titled "Adidas US Sales Data."

# How to Use

1. Download or clone the repository  
2. Open the `Adidas US Final Sales Dashboard.xlsx` file in Excel  
3. Navigate through the dashboard using slicers, charts, and KPIs  
4. Explore the Data Model in Power Pivot for measures and structure


