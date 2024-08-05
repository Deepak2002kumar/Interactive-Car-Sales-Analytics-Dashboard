
# Car Sales Dashboard

## Problem Statement

Our Client is a car dealership company that sells various car models. To effectively track and analyse their sales performance, they need a comprehensive Car Sales Dashboard in Power BI.

## Objective
The objective of this project is to design and develop a dynamic and interactive Car Sales Dashboard using Power BI. The dashboard will visualize critical KPIs related to company's car sales, helping them to understand their sales performance over time and make data-driven decisions.

## Contents

- Car_sales.pbix: The Power BI Desktop file containing the complete report with interactive visuals.

    -->> You can view pbix file [here](https://github.com/Deepak2002kumar/Car_Sales_Trend_PowerBI/blob/main/Car_sales.pbix)
- Car_sales_static_Dashboard.pdf: A static PDF version of the report for quick viewing and sharing.

    -->>   You can download the static PDF Version [here](https://github.com/Deepak2002kumar/Car_Sales_Trend_PowerBI/blob/main/Car_sales_static_Dashboard.pdf)

- Car Sales Raw Data.xlsx: A folder containing the raw data files used to create the report (e.g., CSV, Excel).

    -->> You can download the Excel file [here](https://github.com/Deepak2002kumar/Car_Sales_Trend_PowerBI/blob/8d0a78092cde0818d34802b51f7596c2f410a67a/Car%20Sales%20Raw%20Data.xlsx)

- Problem Statement.pdf: A PDF file containing all the client need and necessity. 
    
    -->> You can download the client need attachment [here](https://github.com/Deepak2002kumar/Car_Sales_Trend_PowerBI/blob/8d0a78092cde0818d34802b51f7596c2f410a67a/Problem%20Statement.pdf)

## Steps followed
### STEP 1 :

Load data into Power BI Desktop, dataset is a excel file. Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options. Perform all necessary data cleaning process from handling duplicates, null values, data types, etc and than save and close the power query editor. 

### STEP 2 (Creating key performance indicators (KPIs) visuals) :
- This is the first report of our dashboard. It will provide real-time insights into key performance indicators (KPIs) related to our sales data. 
- New measures were created to calculate YTD, MTD, PYTD, etc from available columns in our excel data. 
-  A card visual was used to represent all the KPI's values .

NOTE: - ALL SALES VALUES ARE IN '$'.

#### [1] Sales Overview
- YTD Total Sales (Year-to-Date Total Sales):
    - Value: 371.2M
    - This represents the total sales value from the beginning of the year up to the current date.
- MTD Total Sales (Month-to-Date Total Sales):
    - Value: 54.3M
    - This is the total sales value for the current month up to the current date.
- (YTD - PYTD) Total Sales (Year-to-Date minus Previous Year-to-Date Total Sales):
    - Value: 70.8M
    - This indicates the difference in total sales value between the current year and the previous year up to the same date.
- YOY Growth Total Sales (Year-over-Year Growth Total Sales):
    - Value: 23.59%
    - This shows the percentage growth in total sales value compared to the same period last year.
#### [2] Average Price Analysis
- YTD Average Price (Year-to-Date Average Price):
    - Value: 27.99K
    - This represents the average price of cars sold from the beginning of the year up to the current date.
- MTD Average Price (Month-to-Date Average Price):
    - Value: 28.26K
    - This is the average price of cars sold in the current month up to the current date.
- (YTD - PYTD) Average Price (Year-to-Date minus Previous Year-to-Date Average Price):
    - Value: -223.48
    - This indicates the difference in average price between the current year and the previous year up to the same date.
- YOY Growth Average Price (Year-over-Year Growth Average Price):
    - Value: -0.79%
    - This shows the percentage change in the average price compared to the same period last year, indicating a slight decrease.
#### [3] Cars Sold
- YTD Cars Sold (Year-to-Date Cars Sold):
    - Value: 13.26K
    - This represents the total number of cars sold from the beginning of the year up to the current date.
- MTD Cars Sold (Month-to-Date Cars Sold):
    - Value: 1921
    - This is the total number of cars sold in the current month up to the current date.
- (YTD - PYTD) Cars Sold (Year-to-Date minus Previous Year-to-Date Cars Sold):
    - Value: 2616
    - This indicates the difference in the number of cars sold between the current year and the previous year up to the same date.
- YOY Growth Cars Sold (Year-over-Year Growth Cars Sold):
    - Value: 24.57%
    - This shows the percentage growth in the number of cars sold compared to the same period last year.

### Key Takeaways
- Positive Sales Growth:
    
    There is a significant growth of 23.59% compared to the previous year, indicating strong performance and positive sales momentum.
- Declining Average Price:

    There is a marginal decline of 0.79% in the average price, indicating that while sales volume is increasing, the average selling price is slightly lower.
- Increase in Cars Sold:

    There is a noticeable increase in the number of cars sold, as indicated by the YTD cars sold and the YOY growth cars sold.
- Monthly Performance:

    The MTD metrics provide a snapshot of the current month's performance, showing robust sales activity and average prices in line with YTD figures.

### Recommendations:
- Focus on Pricing Strategy: 

    Since there is a slight decline in the average price, consider evaluating the pricing strategy to ensure it aligns with market conditions and maximizes revenue.

#### Preview of KPI's Report page...

![KPI's Screenshot.png](https://raw.githubusercontent.com/Deepak2002kumar/Car_Sales_Trend_PowerBI/main/KPI's%20Screenshot.png)


### STEP 3 (YTD Parameter Analysis using different chart visuals) :

### [ 1 ]  YTD_Sales by Color:
![YTD_sales_by_color_image.png](https://raw.githubusercontent.com/Deepak2002kumar/Car_Sales_Trend_PowerBI/main/YTD_sales_by_color_image.png)

- Pale White: 47.02%
- Black: 33.74%
- Red: 19.24%
Pale White is the most popular car color, followed by Black and Red. This insight can help manufacturers and dealers focus on producing and stocking more pale white cars.

### [ 2 ]  YTD_sales by Dealer Region:
![YTD_sales_by_region_image.png](https://raw.githubusercontent.com/Deepak2002kumar/Car_Sales_Trend_PowerBI/main/YTD_sales_by_region_image.png)

The map shows car sales distributed across different dealer regions in the US. Major sales hubs are in:

- Pasco
- Aurora
- Scottsdale
- Austin
- Janesville
- Middletown
- Greenville

This can help in understanding which regions have higher sales and might require more inventory or marketing efforts.

### [ 3 ] Sales by Body Style:

![YTD_sales_by_body_style_image.png](https://raw.githubusercontent.com/Deepak2002kumar/Car_Sales_Trend_PowerBI/main/YTD_sales_by_body_style_image.png)

- SUV: 26.91%
- Hatchback: 22.3%
- Sedan: 19.85%
- Passenger: 17.09%
- Hardtop: 13.85%
SUVs are the most sold body style, suggesting a preference among customers. This can guide future production and marketing strategies towards SUVs.


### [ 4 ] Weekly Sales Trend:

![YTD_sales_weekly_trend_image.png](https://raw.githubusercontent.com/Deepak2002kumar/Car_Sales_Trend_PowerBI/main/YTD_sales_weekly_trend_image.png)


The sales trend shows a steady increase over the weeks, indicating consistent growth in sales. This can help in understanding the sales momentum and planning for future inventory and sales strategies.

### [ 5 ] Company-wise Sales Analysis:

![Company_wise_trend_image.png](https://raw.githubusercontent.com/Deepak2002kumar/Car_Sales_Trend_PowerBI/main/Company_wise_trend_image.png)

- Top Performers: Chevrolet (27.11M sales, 1043 cars), Ford (25.43M sales, 886 cars)
- Average Price Leader: Cadillac (42.24K average price)

Chevrolet has the highest total sales and units sold, while Cadillac has the highest average price per car sold. This can help in identifying which brands are performing well and which ones command a premium price.

### STEP 4 (Details Grid Showing All Car Sales Information) :
- This is the 3rd report in our dashboard.
- Detailed grid that presents all relevant information for each car sale, including car model, body style, colour, sales amount, dealer region, date, etc.
- Comapny name, Model, Body style, color are in row section of this matrix visual. (you need to click on '+' icon to go deeper and deeper too see each car detail.)
- Dealer_Region is in column section of the matrix. 
- Price ($) / sales is in value section. 
- You can see price of each car sold keeping all parameters in mind. 
- 2 slicers are also used contatining "Year" and "Month" respectively to fetch out information on particular month of a year. 


## Conclusion
The Power BI report provides a comprehensive view of pizza sales performance. By understanding these patterns and customer preferences, strategic decisions can be made to optimize sales, enhance customer satisfaction, and drive business growth.
