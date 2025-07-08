# Sales Trend and Profitabiblity Analysis

## Table of Content

- [Project Overview](#project-overview)
- [Results $ Findings](Results-$-Findings)
- [Problems Solved](problems-solved)
- [Recommendations](#recommendations)

### Project Overview
This project focused on analyzing an e-commerce company’s sales and profit data to uncover key business insights. Using data visualization tools like Tableau, the goal was to identify sales trends, top products, seasonal performance, and areas for growth. The final dashboard helps stakeholders make informed, data-driven decisions.

### Data Sources
Superstore Sales: The primary dataset used for this analysis is Sample - Superstore.xls, containing detailed information about each sales and profit made by the company.

### Tools
- Excel - Data Cleaning [Download here](https://microsoft.com)
- Tableau - Creating reports [Download here](https://www.tableau.com/products/desktop/download)

  ### Data Cleaning & Preparation
Removing duplicates, fixing data types, handling missing values.  
- *Data Structuring:* Organizing raw data before importing into Tableau for visualization.
- Imported raw dataset into Tableau.  
*Created calculated fields* like *Profit Margin* to evaluate profitability.  
- Identified *Underperforming Products* by comparing sales/profit against category averages.  
- Added *Underperforming Flags* to visually highlight low-performing items on your dashboard.  
- Enabled *interactive filtering* for deeper insights by category, region, and product name.

  ### Exploratory Data Analysis
   - Total sales & profit by year/month  
   - Top-selling products  
   - Sales by region and category  
   - Profit margin analysis  
   - Identify underperforming products or regions
 
     ### Data Analysis
     Include some interesting functions
     ```
     [Profit] / [Sales]
     ```
     ```
     IF [Profit] < 29 THEN "Loss" ELSE "Profit" END
     ```
     ```
     IF [Sales] < 229.9 THEN "Underperforming" ELSE "OK" END
     ```
  ### Results $ Findings
  - *Top 3 Products*:  
  - Canon IMAGE CLASS 2200 Advanced  
  - Fellowes PB500 Electric Punch  
  - Cisco TelePresence System EX90  
  These had the *highest sales performance*.
 
- *Peak Sales Month*:  
  - *November* had the *highest sales* with over *$352,461k* in revenue.
 
- *Profitability Insights*:  
  - Some high-selling products had *low profit margins*, indicating a need to reassess pricing or cost structure.
  - Several products - *Top 3 Products*:  
  - Canon IMAGE CLASS 2200 Advanced  
  - Fellowes PB500 Electric Punch  
  - Cisco TelePresence System EX90  
  These had the *highest sales performance*.
 
- *Peak Sales Month*:  
  - *November* had the *highest sales* with over *$352,461k* in revenue.
  - *December* had the *highest sales* with over *$43,369k* in Profit.
 
- *Profitability Insights*:  
  - Some high-selling products had *low profit margins*,like Storex Dura pro Binder,Avery Non-Sticker Binder and KI Adjustable hgh Table indicating a need to reassess pricing or cost structure.
  - Several products were flagged as *underperforming*, meaning they had low sales and profits compared to their category.
 
- *Trends*:  
  - Sales show strong seasonality, peaking in Q4, especially November.
  - Certain product categories consistently outperform others.
 
- *Customer Focus*:  
  - A few product lines are contributing the bulk of revenue—suggesting where to focus marketing and inventory.
 
    ### Problems Solved
- Helped identify which products and months drive the most revenue.
- Uncovered underperforming products that may need promotion or replacement.
- Made it easier for stakeholders to understand performance trends via visual insights.
 
    ### Recommendations
    1. *Focus on High-Performing Products*  
   - Invest more in promoting the top-selling products like *Canon IMAGE CLASS 2200* and *Cisco TelePresence*. Consider bundling them with related items to increase average order value.
 
2. *Re-evaluate Underperforming Products*  
   - Phase out or improve products flagged as underperforming to optimize inventory and reduce storage costs.
 
3. *Improve Profit Margins*  
   - Review pricing strategies for low-margin bestsellers. Explore supplier negotiations or cost-cutting to boost profit without affecting sales volume.
 
4. *Prepare for Seasonal Peaks*  
   - Since November is the peak month, plan inventory, marketing campaigns, and staffing ahead of Q4 to maximize sales.
 
5. *Segment Products by Performance*  
   - Use dashboards to categorize products into high, medium, and low performers for better decision-making and targeted promotions.
 
6. *Monitor Profitability Alongside Sales*  
   - Don’t rely solely on sales volume—track both revenue and profit margin to identify truly valuable products.
  
     ### Limitations
*Problem 1*: *Axis overcrowded due to large data size*  
*Solution*: Aggregated data by month/year and showed top N categories to improve readability.
 
*Problem 2*: *Inconsistent values in Category column*  
*Solution*: Used grouping and manual correction in Tableau’s data pane to standardize values.
 
*Problem 3*: *No clear performance metric initially*  
*Solution*: Created calculated fields for KPIs like profit margin and year-on-year growth.

### Reference
1. [Tableau functions](https://help.tableau.com/current/pro/desktop/en-us/functions.htm)

     
