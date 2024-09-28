# Excel Supply Chain Analysis

## Table of Contents
[1. Project Overview](#project-overview)

[2. Data Preparation](#data-preparation)

[3. Exploring the Data](#exploring-the-data)

[4. Dashboard](#dashboard)

[5. Conclusion](#conclusion)

[6. References](#references)


### Project Overview

This project's purpose was to analyze a large (~180,000 rows) supply chain dataset. I wanted to use Excel to create pivot tables to analyze data and then create a dashboard report to show the most important results. By use of key performance indictators (KPIs), there are revealing insights to the past efficiency of the company's operations. The dashboard will focus on providing important metrics to keep notice on the past three years of orders on an online retail store, which is mainly centred around sports goods and technology.

### Data Preparation

To prepare my data, I checked for duplicates and for missing values. Then converted the sheet to a table, to use filter dropdown to take note of what type of values are present in each field. I noticed the dates for both order date and shipping date were of an improper format. By use of excel formulas, they were converted to a more readable YYYY-MM-DD format. I changed many column names to be more readable and to match the same style as one another. Finally, I used excel formulas (including conditional statements) to make new columns for tracking perfect orders, filled orders and also for the year. 


### Exploring the Data

I examined key fields and their interaction with one another using pivot tables. These included, orders and revenue over time, orders by department, most profitable products, perfect order rate, order fulfillment rate etc. Only the pivot tables that I felt most necessary for the dashboard were kept leading into the next part.

### Dashboard

See below the Excel Dashboard going over data from Q1 2015 - Q4 2017. The dashboard can be filtered by year using the timeline to the right of the title.

![image](https://github.com/aidenLane/excel-supply-chain-analysis/blob/main/Dashboard.png)

### Conclusion

The analysis and dashboard creation revealed many insights into the company's performance. Most notably, it seems that the late orders rate is extraordinarily high at ~45%. Perfect order rate seems to be steady but at a quite low 15-16% each quarter. Metrics like these should reveal the inefficiencies in the supply chain operations and should be addressed to reduce loss. 

Also, assuming this dataset has not had any data entry issues, there is a large drop in sales and profit in the latest quarter recorded (Q4 2017) which is alarming to the business performance. 

This analysis provides many details to indicate poor productivity in the supply chain and more insight into what could be improved.

**Thank you so much for reading!**

### References
- https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis/data
