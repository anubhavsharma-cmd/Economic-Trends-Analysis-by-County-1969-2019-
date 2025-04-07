# Economic-Trends-Analysis-by-County-1969-2019

Economic Trends Analysis by County (1969-2019)

Prepared by: Anubhav Sharma

1. Introduction

This project analyzes economic trends across various U.S. counties from 1969 to 2019. Using Excel for data cleaning, SQL for querying insights, and Power BI for visualization, we identify key economic patterns and industry performances over time.

2. Data Overview

•	Dataset: Profile by County (1969-2019)- https://cumailin-my.sharepoint.com/:x:/r/personal/18bme1161_cuchd_in/_layouts/15/Doc.aspx?sourcedoc=%7B4D8E6CDA-44EA-492B-B0A0-6D431E2E5018%7D&file=Economic-Trends-Analysis-by-County-1969-2019.csv&action=default&mobileredirect=true&wdOrigin=APPHOME-WEB.DIRECT%2CAPPHOME-WEB.BANNER.UPLOAD&wdPreviousSession=63928e22-0f0b-4c9b-92e9-15fc5daa9391&wdPreviousSessionSrc=AppHomeWeb&ct=1743950324507

•	Source: U.S. Government Economic Data

•	Rows: 69,142 | Columns: 59

•	Key Fields:

o	GeoFIPS (County Code) 

o GeoName (County Name)

o Region

o	Industry Classification

o Description 

o Unit

o	Time-series data from 1969 to 2019

3. Data Cleaning (Excel)

•	Handled missing values in GeoName, Region, and IndustryClassification.

•	Standardized numeric formats for economic indicators.

•	Removed duplicate and inconsistent records.

4. Data Storage & Analysis (SQL)

SQL Analysis – Objective & Methodology
 Objective
To analyze U.S. county-level economic data from 1969 to 2019 using SQL to:

Identify top-performing counties and industries

Compare income and GDP trends

Measure growth and decline over time

Provide actionable insights for policy-making, investment, and regional development

 Methodology

1. Data Import

The dataset (profile_by_county_1969_2019.csv) was imported into a relational SQL table called profile_by_county.

Each row represents a unique economic indicator for a county across multiple years (wide format).

2. Table Design

A wide table format was used for storage, with columns for each year from 1969 to 2019.

For analysis, the data was normalized into a long format using SQL or data transformation tools like Power BI or Python.

3. Normalization (Unpivoting)

Created a new table (EconomicData) with the structure:

GeoName | Year | Description | Value

This long format allows for easier filtering, aggregation, and comparison across time.

4. SQL Queries and Analysis

Multiple SQL queries were written to derive insights:

Top 5 Counties by Economic Growth (2010–2019)

Based on personal income growth.

GDP Trend Comparison for Two Counties

Time series analysis for selected counties.

Top Growing Industry (2009–2019)

Compared value change across industries.

Per Capita Income Trends & YoY Growth

Tracked income progression and calculated annual change.

States with Highest Per Capita Income (2019)

Aggregated and ranked performance by state.

Counties with Declining Income (2010–2019)

Detected negative growth for focused improvement.

5. Validation

All queries were tested using sample data before applying to the full dataset.

Aggregates and rankings were verified for correctness.

 Conclusion
This SQL-based analysis provides a powerful, scalable, and flexible way to derive key insights from longitudinal economic data. It can be extended with BI tools like Power BI or Tableau for visualization and storytelling.


6. Data Visualization (Power BI)

Key Dashboards Created:

•	Economic Growth Trends (Line Charts) – Tracks county-wise GDP over time.

•	Industry Comparison (Bar Chart) – Shows top-performing industries.

•	Geographical Economic Heatmap – Highlights economic density by region.

6. Insights & Findings

•	Major Economic Growth Areas: Certain counties exhibited significant GDP growth post-2000.

•	Top Industries: Industries like technology and healthcare saw exponential growth.

•	Regional Disparities: Some regions lag behind in economic progress due to various factors.

7. Conclusion & Next Steps

This study provides an in-depth analysis of economic trends across counties. Future work can explore factors influencing economic 
disparities and forecasting future trends using machine learning.
________________________________________

