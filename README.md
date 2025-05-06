# Analysis-And-Visualization-of-Myseller-Global-Sales
This repository details the analysis and visualization of Myseller sales dataset from 2019 - 2021

## Introduction
This repository contains data analysis and visualization project based on the Myseller Global Sales Dataset, with insights generated using Power Bi. The dataset contains global order transactions, capturing important attributes such as order date, product category, region, units sold, sales channel (online/offline), profit, delivery timelines and customer countries. It also includes a supplementary dataset for GDP (nominal) data of Sub-Saharan African countries, used for comparative economic analysis.

## Objectives
- Analyze Global Sales Performance: Identify trends in revenue, profit and units sold across different regions, product categories and sales channel.
- Evaluate Channel Effectiveness: Compare online vs offline sales to determine which channel drives more profit.
- Understand Regional Dynamics: Explore sales and delivery patterns across global regions to highlight top and underperforming markets.
- Track Temporal Trends: Visualize how sales and profits change over time, especially focusing on monthy performance in 2021.
- Measure Operational Efficiency: Calculate average delivery times and identify which regions experience the fastest or slowest shippiing.
- Rank Country-Level Performance: Highlight top and bottom countries by order volumes to support targeted decision-making.
- Assess Economic Potential: Investigate the relationship between GDP and sales in Sub-Saharan Africa to explore market opportunities.
- Build Interactive Visualizations: Develop a Power Bi dashboard that makes complex insights accessible, visually compelling and decision-ready.
 
## Tools
- Excel
- Power Bi
- Wikipedia(GDP table) 

## Techniques and skills
- Data Cleaning and Preparation
- Data modelling
- Time Intelligence
- Performance Analysis
- Correlation Analysis
- Interactive Dashboard
- Data Analysis Expressions(DAX)
- Data Visualization

## Data source
<a href = "https://github.com/Dinmaaaa/Analysis-And-Visualization-of-Myseller-Global-Sales/blob/main/Mysellar%20Global%20Sales%20Dataset.xlsx"> Myseller Global Sales Dataset </a>

<a href = "https://en.wikipedia.org/wiki/List_of_African_countries_by_GDP_(nominal)"> List of African Countries by GDP (nominal) </a>

## Data Model
The data was first normalized in excel before being transformed in Power Query. A supporting table with list of african countries by nominal GDP was then created and added for economic correlation analysis. A one-to-many relationship connects the Country field in the GDP to the Country field in the Orders table

![Data Model](https://github.com/Dinmaaaa/Analysis-And-Visualization-of-Myseller-Global-Sales/blob/main/images/Myseller_global_sales_data_model.png)

## Recommendations
- Prioritize Online Sales Channels: The online channel consistently generated higher profit margins compared to offline sales. Expanding online presence and optimizing digital marketing could significantly increase total revenue.
- Improve Shipping Efficiency in Key Markets: Some regions, particularly those with higher order volumes, experience longer average delivery times. Optimizing logistics in those areas could improve customer satisfaction and retention.
-  Re-evaluate Underperforming Product Categories: Product categories that show declining trends or low profitability over time should be reviewed. Consider reducing investment in these categories or investigating potential causes such as pricing, quality, or market saturation.
- Expand in High Order Volume Countries: Countries with consistently high order volumes, even with moderate GDP, could be further cultivated through targeted promotions, loyalty programs, or exclusive offers.
- Monitor Profitability vs. Volume: High sales volume doesn't always mean high profit. Mysellar should monitor product and regional profitability alongside sales volume to ensure sustainable growth.

## Download
<a href = "https://github.com/Dinmaaaa/Analysis-And-Visualization-of-Myseller-Global-Sales/blob/main/images/Myseller_global_sales_dashboard.pbix"> Download the Power Bi file </a>
