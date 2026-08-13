
# Customer Sales Dashboard | Power BI


Problem Statement

The goal of this project is to transform raw customer sales data into an interactive and easy-to-understand Power BI dashboard. The analysis focuses on evaluating overall sales, profit, orders, and average order value, while also understanding performance across different products, product lines, cities, time periods, and promotion types. The dashboard helps identify sales trends, top-performing products and locations, and the relationship between sales and profitability, supporting better understanding of business performance and data-driven decision-making.

Project Workflow

step 1.Imported the raw and uncleaned sales data from Excel into Power BI.

step 2.Cleaned and transformed the data using Power Query.

step 3.Prepared the cleaned data for analysis and visualization.

step 4.Created DAX measures to calculate Total Sales, Total Profit, Total Orders, and Average Order Value.

step 5.Created KPI cards and different visuals such as bar charts, line charts, scatter plots, and a map visual.

step 6.Designed an interactive Customer Sales Dashboard with a Promotion Name filter.

step 7.Analyzed sales performance across different products, product lines, cities, time periods, and promotion types.

Key KPIs

.Total Sales

New measures was created to find Total Sales

    Total Sale = SUM('Fact Table'[Total Sales])
Card Visual is used to represnent Total Sales


.Total Profit

New measures was created to find Total Profit

     Total Profit = SUM('Fact Table'[Profit])
Card Visual is used to represnent Total Profit

.Total Orders

New measures was created to find Total Orders

    Total Order = DISTINCTCOUNT('Fact Table'[OrderID])
Card Visual is used to represnent Total Orders

.Average Order Value

New measures was created to find Average Order Value

     Avg Order Value = DIVIDE([Total Sale],[Total Order])
Card Visual is used to represnent Average Order Value

         ALL Card Visual Represented below

![Image](https://github.com/user-attachments/assets/37c20c9a-9456-4745-8bff-ea21565fda48)

Outcomes

This project demonstrates practical skills in Power BI, Power Query, DAX, data cleaning, data analysis, and data visualization by transforming raw Excel data into an interactive business dashboard.

![Image](https://github.com/user-attachments/assets/864f369e-3402-44d1-892a-ee5e041e06a9)



