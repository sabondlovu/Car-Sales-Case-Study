# Car-Sales-Case-Study
Analysis for a Car Sales Case Study

Data Stuido: https://datastudio.google.com/s/jFaSXdac25A

Loavble: https://drive-data-glow.lovable.app/car-analysis

1. Project Overview
This project was developed for Bright Motors to assist a newly appointed Head of Sales in expanding the dealership network and optimizing inventory.
As a Junior Data Analyst, I extracted actionable insights from historical car sales data to guide future sales and marketing strategies.

2. Objectives
- The primary goals of this analysis were to identify:

- Which car makes and models generate the most revenue?

- The relationship between vehicle price, mileage, and year of manufacture.

- Regional sales performance by location.

- Emerging trends in customer purchasing preferences.

- Recommendations for increasing dealership profitability.

 3. Tech Stack Planning:
   - Miro (Architecture & Data Flow).
   - Data Processing: Databricks (SQL).
   - Visualization: Google Looker Studio and Lovable 
   - Presentation: Microsoft PowerPoint.

4. Data Architecture & ETL Pipeline
- The data flow follows a structured pipeline as outlined in the project planning phase:
- Source Layer: Raw car sales data (CSV format).
- ETL Layer (Databricks SQL): 
- Converted text-based prices to numeric formats.

- Calculated Total Revenue (Selling_Price * Units_Sold).

- Categorized vehicles into Performance Tiers (High, Medium, and Low Margin).

- Analysis Layer: SQL queries were used to group data by Make, Model, Year, and Region.
Presentation Layer: Interactive dashboards created in Google Looker Studio.

5. Key Calculations Used

Total Revenue: Selling Price * Units Sold.
Calculated the profit margins 

6. Key Insights
Top Revenue Generators: Analysis of high-performing makes and models.

Profitability: Categorization of inventory into performance tiers to identify high-margin stock.

Regional Trends: Identification of cities or provinces with the highest sales volumes.

7. Project Files

- car_sales_queries.sql: SQL scripts used for data cleaning and transformation.

- car_sales_processed.xlsx: The final cleaned dataset used for visualization.

## 8. Strategic Recommendations
Based on the data analysis, the following actions are recommended for the Head of Sales:
1. Inventory Optimization - stock acquisition for car makes and models, maximize on the high margin performance cars, to maximize profitability
2. Pricing Strategy - implement dynamic pricing for older vehicle models with high mileage to maintain a competitive average selling price and increase turnover.
3. Profitability Monitoring: Conduct quarterly reviews of the column across all regions 




- BrightMotors_Presentation.pdf: Final report for the Head of Sales.

- Role: Junior Data Analyst

Dataset: Bright Car Sales 
