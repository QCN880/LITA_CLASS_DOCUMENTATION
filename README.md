
# LITA_CLASS_DOCUMENTATION

## Table of content
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Data sources](#data-sources)
- [Excel file columns](#excel-file-columns)
- [Tools used](#tools-used)
- [Formulas used](#formulas-used)


### Project topic :Comprehensive Sales Performance Dashboard


### Project overview 
---
This Comprehensive Sales performance  dashboard is developed to monitor and analyze sales performance across various regions,market and stores  enabling data-driven decision-making for business growth and optimization.

##### An image of the entire dashboard
![Screenshot 2024-11-20 134147](https://github.com/user-attachments/assets/fb74b616-291a-4543-9ed1-036eceba3065)

### Objectives
---
The objective of this dashboard is to :
 1. Analyze sales trends and identify areas of growth.
 2. Develop data-driven recommendations to optimize sales strategies.
 3. Create interactive dashboards for stakeholder communication.


### Data sources
---
The primary source of Data used here is pivot table.xls

Click on the link below to download the data

[Download here](www.google.com)

### Excel file columns
---
The Excel file used (pivot table.xls) contains the following columns

1. Regions: Contains six geo political zones in Nigeria (e.g south west,North East )
2. Market: Specific markets or segments
3. Store:Includes Individual store names in the location
4. Trade Date: Displays the date of the transaction
5. Fiscal Period: Accounting periods (e.g., Q1, Q2)
6. Model: Product models or SKUs
7. Line of Business:Includes the various categories of business operations
8. Day Category: Classification of days (e.g., Workday,public holiday etc)
9. Revenue: Indicate the sales revenue generated
10. Units Sold: indicate the Number of units sold
11. Transaction Category : Includes the type of transaction carried out

### Tools used
---
 -	Microsoft Excel: Advanced formulas, PivotTables, Pivot charts
 -	Data Visualization: Charts, Graphs, Slicers, Timelines
 -	Documentation: README.md, Project Report (PDF)
 -	GitHub for portfolio building

   ### Formulas used
   ---
   The formula used for the analysis of the data and preparation of the dashboard are shown below.
   ```Excel functions and formula
  Revenue Growth Rate = (B3 - B2)/B2

  Revenue per unit sold = Revenue/unit sold

  =IF(J1138<=20,"Low",IF(J1138<=50,"Medium","High"))
  
   ```
### Data cleaning and  formating
---
The data , Pivot table.xls was cleaned by :
 1. Checking and removing blanks
 2. Checking and deleting duplicate rows
 3. Triming whitespaces
 4. Grouping transaction category into low,medium and high

### Data analysis

### Dashboard Features
---
#### 1. Interactive filters
  - Slicers and Timelines for dynamic data filtering by Region ,Transactin date ,Month and Day Category

    ##### Slicer-Filter by Region
    
    ![Screenshot 2024-10-14 124142](https://github.com/user-attachments/assets/d37e4942-2170-4743-b420-fc4eef91b76b)

    Timeline- Filters by Transaction date,year,quaters and month
    

#### 2. Key performance indicators(KPI)
  - Primary KPIs:
    1. Total Revenue: Aggregated revenue across selected filters.
    2. Total Units Sold: Aggregated units sold across selected filters.
    3. Revenue Growth Rate: Percentage increase or decrease in revenue over periods.
    4. Sales Trends:Yearly and quarterly revenue and units sold trends.
 - Secondary KPIs:
    1. Average Revenue per Unit: Revenue divided by units sold.
    2. Models by Revenue: Identification of highest revenue-generating product models.
    3. Revenue by Line of Business: Breakdown of revenue across different business lines.
    5. Revenue by market: Identification of top six market based on the revenue generated.

 #### Visualizations
 ---
   Sales Trend : A combined graph showing the rate of sales by revenue and numbers of unit sold 
   
 ![Screenshot 2024-10-14 151041](https://github.com/user-attachments/assets/3228b562-e3dc-469f-bf2b-f3d976c8045b)

 ##### Revenue by Line of business : The pie chart below shows how the revenue generated is affected by the line of business
 
![Screenshot 2024-10-14 153323](https://github.com/user-attachments/assets/f3437e09-df3b-42ab-a505-1e7d4eb235fa)
 

### Video
A detailed video showing the entire dashboard and how the revenue generated is affected by the regions by using the Region slicer
It also shows the revenue generated each year and how they depend on the unit sold,region,line of business,maket and models

### Exloratory data analysis
---
EDA involved the exploring of the Data to answer some questions about the Data such as;

- What is the overall sales trend
- Which product are top seller?
- What are the products on peak sales?
  
### Data analysis 
---
``` SQL
SELECT *FROM SALARY
WHERE STAFF ID = AB123
```

### Data visualization 
