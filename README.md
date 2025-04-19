# Hotel-Operations-Analysis

## Introduction 
The hospitality industry is highly competitive and data-driven. With increasing online bookings, changing customer behaviors, and the impact of cancellations on revenue, hotels need smart insights to optimize their operations, pricing, and marketing strategies. This project analyzes hotel booking data to uncover trends in customer behavior, booking patterns, and revenue generation.

Using tools like Excel, SQL Server, and Power BI, the dataset is cleaned, explored, and visualized to help stakeholders make informed decisions. Key areas of focus include booking trends, cancellation patterns, seasonal performance, customer segmentation, and revenue insights.

## Problem Statement
Hotel businesses often face challenges such as high cancellation rates, inconsistent revenue flow across seasons, and limited visibility into customer booking behaviors. Without proper analysis, it's difficult to:

- Identify which segments contribute most to revenue.

- Optimize room pricing and marketing strategies.

- Anticipate customer demand across different times of the year.
  
The goal of this analysis is to explore hotel booking data and uncover actionable insights that can help:

## Data Cleaning 
The dataset was cleaned by standardizing column names, fixing inconsistencies in text and dates, and handling missing values such as replacing blanks in the children column with 0 and undefined meal entries with the mode. Additional improvements included correcting week numbers, adding a Booking ID, converting country codes to full names, and replacing zero adr values with the average. Finally, the file was converted to a UTF-8 CSV for SQL compatibility, ensuring a structured and analysis-ready dataset.

## Modeling 
The model is a star schema.
There are 9-dimension tables and 1 fact table. The dimension tables are all joined to the fact table one 
to-many relationship.
![](model.png)

## Visualization
The visualizations present key insights into customer behavior, booking trends, and revenue performance. Through interactive charts, they support data-driven decisions to optimize hotel operations and marketing strategies.

![](Firstvis2.png)  
### Top KPIs (Cards at the Top)
- Cancelation Rate % (37%):
Shows that 37% of all bookings were canceled – a significant portion, which could point to a customer trust or policy issue.

- Total Bookings (119.39K):
  Indicates the total number of bookings made across the dataset.

- Total Revenue (31.57M):
Reflects the total income generated from all bookings.

Origin of Top 5 Customers
Insight:
Portugal leads by far with 49K bookings, followed by the UK and France. This shows where most guests are coming from and can guide targeted marketing efforts.









![](secondvis2.png)







