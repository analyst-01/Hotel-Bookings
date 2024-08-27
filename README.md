# GTE Rides- Bike Purchase Analysis

![](https://github.com/analyst-01/Hotel-Bookings/blob/main/hotelpic.jpg)
___
## Introduction
This project was carried out to demonstrate how to import Excel file to SQL Server for manipulations, and then exported to Power BI for reports and interactive dashboard.

**_Disclaimer_**: _The dataset and all the reports in this analysis do not represent any real company or entity. It's just for demonstration of Excel skills_.

## Problem Statement
C & R Ltd has two types of hotels- City Hotels And Resort Hotels. The management wants to know if their hotel revenues are growing by year. Should increase parking lot size be increased? 

For the analysis, the problem statement is broken into specific evaluation questions:

1. Were the hotel revenues growing yearly for both hotel types?
   
2. Was there an increase in guests coming with personal cars?

3. What were the average daily rate and guests?

## Skills/Concepts Demonstrated
Microsoft Excel, SQL Server, and Power BI were used for this analysis. The following skills were demonstrated;

- Importing an Excel file to SQL Server
  
- Combining tables and creating a new column with SQL
  
- Using Power BI Report

- Creating an interactive dashboard

## Getting the Data
The file containing the data was downloaded from a website. You can access the file [here](https://absentdata.com/wp-content/uploads/2021/05/hotel_revenue_historical_full-2.xlsx).
 It has 5 worksheets: 2018, 2019, 2020, Meal and Market_Segment. 

## Investigating the Data
The dataset was checked for relevance to the evaluation questions. Also, the use of the data did not breach any data-related laws.

## Preparing the Data/ Data Transformation
- HotelBookings database was created for the analysis. The file was imported into SQL Server as tables.
- The tables were combined with "UNION".
- A column, revenue, was created.

## Analysis and Visualizations
Pivot Tables were created from 4 columns: Age Group, Children, Income and Purchased Bike to summarise the desired data.
To visualize the trends and patterns in the analysis, slicers, bar chart and line chart were used.

### Pivot Tables 

![](p_table.png)   | ![](p_table2.png)

### Findings:

- Out of 276 adults, 110 bought bikes. Out of 614 young adults, 332 bought bikes, and only 39 out of 110 youths bought bikes.
- Adults and Youths with lower average incomes bought bikes while young adults with higher average incomes bought bikes.
- It was observed that there were fewer children in the families of bike buyers compared to non-buyers. 

### Interactive Dashboard 
![](dashboard.png)

You can interact with the dashboard [here](BikeProject.xlsx).

## Conclusion and Recommendations

From the dataset, many questions could still be answered. As for this analysis, here are my recommendations based on the findings:
1. GTE Bikes' marketing campaigns should  be targeted at adults with low incomes, and young adults with high incomes.
2. The chance of bike sales is high if low-income adults and high-income young adults with children are targeted in the campaign.
3. It is recommended that the cost of marketing to people between 30 years and below should not be too high because they averagely earn lower income compared to adults and young adults. Moreover, out of 110 youths surveyed, only about 35% of them bought bikes.
