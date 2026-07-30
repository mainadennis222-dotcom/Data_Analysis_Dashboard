# Data_Analysis_Dashboard
This end-to-end Excel project involves gathering, transforming, and visualizing coffee bean sales data to create a dynamic dashboard .

The primary goal was to analyze sales trends over time, identify top-performing regions, and understand customer preferences based on coffee type, roast, and loyalty status.

**Data Processing & Transformation**
The project utilized three primary data tables: Orders, Customers, and Products
_Key transformation steps included:_

Data Gathering: Used XLOOKUP to pull customer information (names, emails, countries) and INDEX MATCH for dynamic product data retrieval

Applied IF functions to handle missing values (e.g., replacing zeros in email fields with blanks) and standardized coffee names from abbreviations to full titles (e.g., "ROB" to "Robusta")

Formatting: Created custom number formats for the "Size" column to include "kg" metrics and formatted "Order Date" with abbreviated month names for better clarity

Table Conversion: Converted the data range into an official Excel Table ("orders_table") to ensure pivot tables and charts update automatically when new data is added

**Key Performance Indicators (KPIs) & Insights**
The dashboard tracks several critical business metrics:

Total Sales Over Time: Analyzes revenue trends across four coffee types: Arabica, Excelsa, Liberica, and Robusta

Regional Performance: A bar chart comparing sales across the United States, Ireland, and the United Kingdom

Customer Loyalty: Tracks the top five customers by total sales volume to identify high-value clients

Product Preferences: Filters sales by roast type (Light, Medium, Dark) and package size (0.2kg to 2.5kg) to see which configurations drive the most revenue

**Visualizations & Interactivity**

The final dashboard was designed for high interactivity and a professional "app-like" feel:

Line Chart: Displays total sales over time, customized with specific colors for each coffee type for easy differentiation

Bar Charts: Visualize sales by country and identify the "Top 5 Customers"

Timeline: Allows users to filter all visuals by selecting specific months or years

Slicers: Three interactive slicers for Roast Type Name, Size, and Loyalty Card status, all connected across multiple pivot tables to ensure the entire dashboard updates simultaneously

UI/UX Enhancements: Gridlines, row/column headers, and the formula bar were hidden to create a clean, professional dashboard interface

**Tools Used**

Advanced Formulas: XLOOKUP, INDEX MATCH, Nested IF functions

Data Visualization: Pivot Tables, Pivot Charts, Timelines, and Slicers

Design: Custom formatting, RGB color coding, and UI optimization for a professional dashboard look

**Data Set Used**

<a href= "https://github.com/mainadennis222-dotcom/Data_Analysis_Dashboard/blob/main/coffeeOrdersData.xlsx">Dataset</a>
