# Superstore-Sales-Dashboard -- PowerBI Project 

# Interactive Dashboard Link : https://app.powerbi.com/groups/me/reports/32f81a4b-41e4-4a5c-a623-db705521c213/80e0519c0e7ddc92acc3?experience=power-bi

# Dashboard Preview:-
![Superstore Sales Dashboard Image ](https://github.com/user-attachments/assets/bb3d129f-bbd6-45bf-8ac6-df33bfaa2df6)

## Objective
The objective of this project is to develop an interactive Sales Dashboard using Power BI. This dashboard provides stakeholders with actionable insights into sales performance by visualizing key metrics and trends. The focus is on delivering an easy-to-navigate and interactive interface for effective decision-making.

## Project Description
This project involved importing raw sales data, transforming and cleaning it, creating a robust data model, and designing an interactive dashboard using Power BI. The dashboard includes a variety of visualizations, such as bar charts, line charts, and pie charts, which represent sales metrics, trends, and comparisons. Additionally, DAX (Data Analysis Expressions) was used to create calculated columns and measures for advanced analytics.

### Step-by-Step Process
- Data Cleaning and Transformation
  
  -- Tool Used: Power Query Editor
  
  -- Removed duplicate entries and handled missing or null values.

  -- Standardized column names for consistency.
  
  -- Changed data types (e.g., dates, numbers, categories) to align with their intended use.

  -- Added calculated columns (e.g., Sales = Quantity × Unit Price) for essential metrics.
- Data Modeling

  -- Established relationships between tables, such as linking sales data with customer and product details.

  -- Created a star schema to optimize data modeling and improve query performance.

  -- Marked the date table as a "Date Table" for time-based analysis.
- Dashboard Design and Visualizations
  
  -- Designed an intuitive dashboard layout with the following charts:

#### Charts Used:
- Bar Chart:
  
  -- Used to compare sales by region or product categories.

  -- Displayed "Total Sales by Region" to highlight geographic performance differences.
- Line Chart:
  
  -- Used to show sales trends over time.

  -- Plotted "Monthly Sales Trend" to identify patterns and seasonality.
- Pie Chart/Donut Chart:
  
  -- Used to display the proportion of sales by category or segment.

  -- Showed "Sales Contribution by Product Category."
- Stacked Bar Chart:
  
  -- Used for comparing regional sales with product breakdowns.

  -- Represented "Regional Sales Contribution by Product Line."
- KPI Cards:
  
  -- Used to highlight key metrics such as total sales, total profit, and average sales per order.
- Slicers:
  
  -- Enabled users to filter data by region, product category, and date range.
- DAX Measures and Calculations
#### DAX Functions Used:

  -- SUM: For calculating total sales (Total Sales = SUM(Sales[Amount])).

  -- CALCULATE: To create measures for specific conditions (e.g., sales in a specific region).

  -- DATEADD: Used for time intelligence (e.g., comparing this year’s sales with last year’s).

  -- AVERAGE: For finding average order value (Average Order Value = AVERAGE(Sales[Amount])).

  -- Measures were used in charts like bar charts and line charts to dynamically calculate total and average sales.

  -- DAX measures ensured consistency in metrics across visualizations.
- Interactivity and User Experience

  -- Added slicers for region, category, and time to allow users to explore data interactively.

  -- Enabled drill-through options to analyze specific details like sales performance by individual products.
- Performance Optimization
  
  -- Optimized data models by removing unnecessary columns and summarizing data.

  -- Minimized the number of visualizations on a single page to improve loading times.
- Testing and Validation
  
  -- Cross-referenced results with raw data to validate accuracy.

  -- Ensured interactivity features worked as intended.
- Deployment

  -- Published the dashboard to Power BI Service for accessibility.

  -- Shared links with stakeholders and configured appropriate permissions.
## Conclusion
This Sales Dashboard project showcases the ability to clean and transform data, create a data model, and design an interactive dashboard in Power BI. By leveraging DAX measures and advanced visualizations, it provides stakeholders with clear insights into sales performance. The dynamic nature of the dashboard ensures that it can be customized for different business scenarios, making it a valuable tool for decision-making.



