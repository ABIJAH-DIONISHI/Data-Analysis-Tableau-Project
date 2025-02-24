# Data-Analysis-Tableau-Project
# ATLIQO  HOSPITALITY REVENUE ANALYSIS

BUSINESS OBJECTIVE:

Provide Insights to the Revenue Team in the Hospitality Domain

•	AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management. 

•	The managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

PROJECT SCOPE:

     1.Create the metrics according to the metric list.
     2.Create a dashboard according to the mock-up provided by stakeholders.
     3.Create relevant insights that are not provided in the metric list.
     4.Identify the data sources pertaining to revenue management
     5.Create a revenue dashboard that measures important KPIs
     6.The dashboard should depict both high level and granular insights.

SOLUTION APPROACH:

     1.There are 5 tables provided for tracking revenue, 3 dimension tables (date, hotel, room) and 2 fact tables (bookings, aggregated bookings).
     2.The relationships/Cardinality between the tables were created in Tableau Pane and extract was generated  so that main file doesn’t get affected.
     3.The tool used for creating the visualization/dashboard Tableau Public.


A few measures were created to calculate the KPIs as shown below:

       1.Total Revenue = Sum of revenue_realized from Bookings table (in Rs.)
       2.Total bookings = Count of booking_id from Bookings table
       3.Avg rating = Average of ratings from Bookings table
       4.Total capacity = Sum of capacity from Aggregated bookings table
       5.Total successful bookings = Sum of successful bookings from Aggregated bookings table
       6.Occupancy rate = Total successful bookings / Total capacity (in %)
       7.Total cancelled bookings = Count of booking_id File display us='cancelled' from Bookings table.
       8.No.of Days = count of date from dim_date table


 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------

