# Financial-Sales-Performance-Analysis
## Project Objective
This project involves a comprehensive financial analysis of sales, profit, and units sold across various global segments and products. The final deliverable is a performance dashboard visualizing key business metrics and trends to support data-driven decision-making.


## Dataset Used
- <a href="https://github.com/amanbhatt007/Financial-Sales-Performance-Analysis/blob/main/Financial%20Sample(microsoft).xlsx">Financial Sales Dataset</a>


##  Questions (KPI)
- What is the Total Revenue and Total Net Profit generated over the analyzed period?
- What is the Overall Profit Margin for the entire company?
- Which Country is the most profitable (highest Net Profit)?
- How do Sales and Units Sold compare across all countries (e.g., Canada vs. France)?
- Which Product category is the top seller by volume (Units Sold) and by value (Sales)?
- Which Customer Segment (e.g., Government, Midmarket, Enterprise) yields the highest Profit?
- What is the percentage contribution of each Product or Country to the total company profit?
- What is the monthly and yearly trend for Sales and Profit? (Are we growing?)
- Was there any seasonal spike in sales or profit, and in which month did it occur?
- How does applying a High Discount band affect Units Sold compared to a Low or None discount band?
- Which discount strategy (Discount Band) delivers the best Profit? (High sales but lower profit, or lower sales but higher profit?)
- What is the profitability trend for our flagship product (Velo or Carretera) in our biggest market (United States of America)?
- What is the average Sale Price or Manufacturing Price by Product?

- Dashboard Interaction <a href="https://github.com/amanbhatt007/Financial-Sales-Performance-Analysis/blob/main/Project%203%20dashboard.png">View Dashboard</a>


## Process
🛠️ Phase 1: Data Preparation (Power Query Editor)
Extract & Load: Start Power BI Desktop, use Get Data (Excel Worksheet), and load the <a href="https://github.com/amanbhatt007/Financial-Sales-Performance-Analysis/blob/main/Financial%20Sample(microsoft).xlsx">Financial Sales Dataset</a> file. 
<img width="1763" height="948" alt="Project 3 dataset" src="https://github.com/user-attachments/assets/352abcc9-e1e8-4c7e-9569-74dd6592807d" />

Click "Transform Data" to open the Power Query Editor.

<img width="1920" height="1080" alt="Project 3 power bi" src="https://github.com/user-attachments/assets/634b822a-406b-4b33-bf3e-e58944f5e5ca" />

Ensure Headers: Verify that the first row is correctly set as the column headers.

Correct Data Types: Set all columns to the appropriate type:

Date: Date column.

Text/Categorical: Segment, Country, Product, Discount Band.

Decimal Number/Currency: Units Sold, Manufacturing Price, Sale Price, Gross Sales, Discounts, Sales, COGS, and Profit.

Load to Model: Click "Close & Apply" to load the cleaned data into the main Power BI data model.

🔗 Phase 2: Data Modeling and Measures (DAX)
Create Key Measures: In the Report View, define explicit DAX measures (Key Performance Indicators) for accurate aggregation:

Calculate Total Sales, Total Profit, and Total Units Sold.

Calculate the Profit Margin % using the formula: DIVIDE([Total Profit], [Total Sales]).

📊 Phase 3: Visualization and Insight Delivery
Set up Layout: Design the report canvas, adding a clear title (e.g., "Global Financial Sales Performance") and establishing a visually appealing, professional layout.

Build Core Visuals: Populate the dashboard with specific visuals designed to answer the project's key business questions:

KPI Cards: Display Total Sales and Total Profit (Financial Health Insight).

Line Chart: Show Sales and Profit Trends over time (Seasonality and Growth Insights).

Bar/Column Charts: Show Profit by Country and Sales by Product (Top/Bottom Performer Insights).

Distribution Visuals: Use charts to visualize how different Discount Bands impact the resulting Profit (Strategy Effectiveness Insight).

Add Interactivity: Add Slicers for Country, Segment, and Year to allow the user to filter the data and drill down into specific performance areas.

Format for Clarity: Apply consistent colors, clear axis labels, and conditional formatting (e.g., highlighting negative profit in red) to ensure the Data Visualization Dashboard is made to show immediate, actionable insights for business stakeholders.


## Dashboard
<img width="1608" height="853" alt="Project 3 dashboard" src="https://github.com/user-attachments/assets/d9434763-093e-4e0a-a63f-46cddb2e0e33" />



