Irish Retail Analytics & Demand Forecasting Project
Complete BI & Business Analysis Solution
1. Project Overview

This project delivers an end-to-end Retail Analytics and Demand Forecasting solution tailored for the Irish retail sector.
The goal was to integrate sales, pricing, inventory behaviour, and economic indicators into a single analytical system using Power BI and Business Analysis practices.

The solution includes both the technical analytics components and full BA documentation, demonstrating combined capability across BI, data modelling, requirements analysis, and strategic reporting.

2. Key Objectives

Provide a clear understanding of sales performance and demand patterns across time.

Identify slow-moving and high-demand items to support inventory optimisation.

Analyse price sensitivity and promotional effectiveness.

Evaluate business performance in the context of inflation and CPI movements.

Deliver a multi-page interactive Power BI dashboard supported by professional BA documentation.

3. Dashboard Components
Page 1: Sales Performance Overview

Total Units Sold and Revenue KPIs

Monthly and yearly sales trends

Category and store comparisons

Item-level drilldowns

Page 2: Demand & Inventory Insights

Rolling 7-day and 30-day demand metrics

Identification of slow-moving items

High-demand product ranking

Item–store performance heatmap

Inventory alerts

Page 3: Pricing & Promotion Analytics

Price–demand relationship analysis

Promotional uplift and demand spikes

Sensitivity differences across product categories

Seasonality in price-driven behaviour

Page 4: Irish Economic Context

CPI trend aligned with sales

Inflation-adjusted sales performance

Retail Index KPI for market context

4. Data Model

A star schema was implemented to support efficient analysis.

Fact Table

Fact_Sales: item_id, store_id, date, units_sold, revenue

Dimension Tables

Calendar

Products

Stores

Sell Prices

CPI (Ireland)

Retail Sales Index (Ireland)

This structure allows for scalable, high-performance reporting and robust DAX calculations.

5. Key DAX Measures

Total Units Sold

Total Revenue

Rolling 7-Day Sales

Rolling 30-Day Sales

Inflation-Adjusted Sales

CPI Index

YOY Inflation

High-Demand and Low-Demand Flags

Price Sensitivity Measures

Promotional Uplift

6. Business Analysis Deliverables

This project includes full BA documentation to demonstrate capability beyond BI development.

Deliverables include:

BA Portfolio Write-Up (2–3 pages)

Business Requirements Document (5–7 pages)

Stakeholder Analysis

Functional and Non-Functional Requirements

User Stories and Acceptance Criteria

AS-IS and TO-BE Process Descriptions

This reflects how an analytics project is executed in a real commercial environment.

7. Key Insights from the Analysis

Demand displayed wave-like patterns rather than steady growth, indicating strong seasonality and behavioural cycles.

Significant performance variation across stores, with high-volume stores exceeding 11 million units while others held considerably lower output.

Slow-moving items presented substantial stock risk, while high-demand items showed clear replenishment priority.

Promotional events triggered notable demand spikes, particularly in the FOODS category.

Inflation-adjusted analysis revealed that some apparent growth periods were driven by rising consumer prices rather than increased demand.

8. Tools and Technologies Used

Power BI

Power Query

DAX

SQL (supporting analysis)

Business Analysis Frameworks

Data Modelling

Irish CSO datasets

Retail and pricing analytics techniques

9. Repository Structure
Retail-Analytics-Ireland/
│
├── README.md

├── Dashboard.pdf
├── Business-Requirements-Document.pdf
├── BA-Writeup-Portfolio.pdf
     

10. Business Value

This solution enables Irish retail organisations to:

Improve replenishment and stock allocation

Optimise pricing and promotional strategies

Interpret sales performance in real economic terms

Reduce manual reporting workloads

Enhance strategic planning with data-backed insights

11. Future Enhancements

SQL Supply Chain Analytics extension

Retail pricing and promotions SQL analysis

Machine learning forecasting model

Integration with Fabric Lakehouse

Automated refresh pipelines
