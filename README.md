OLA Ride Booking Analytics | SQL Server & Power BI
Overview

An end-to-end Data Analytics project built using MS SQL Server and Power BI to analyze OLA ride booking operations. The project transforms raw ride-booking data into actionable insights through SQL analysis, KPI reporting, and interactive dashboards.

Project Workflow
Plain Text
Raw CSV Dataset
↓
MS SQL Server
↓
SQL Analysis & Reporting
↓
Power BI Data Modeling
↓
Interactive Dashboards
↓
Business Insights & Recommendations
Tools & Technologies
MS SQL Server
SQL
Power BI
DAX
CSV Dataset
Repository Structure
Plain Text
OLA-Ride-Booking-Analytics/
│
├── Dataset/
│ └── ola_bookings.csv
│
├── BRD/
│ └── Business_Requirements_Document.pdf
│
├── SQL Queries/
│ └── OLA_Analysis_Queries.sql
│
├── Dashboard/
│ ├── OLA_Dashboard.pbix
│ └── OLA_Dashboard.pdf
│
├── Insights & Recommendations/
│ └── OLA_Project_Insights.pdf
│
├── Screenshots/
│ ├── Overall.png
│ ├── Vehicle_Type.png
│ ├── Revenue.png
│ ├── Cancellation.png
│ └── Ratings.png
│
└── README.md
Business Requirements

The reporting solution was designed to analyze:

Booking Performance
Vehicle Performance
Revenue Trends
Customer Behavior
Cancellation Analysis
Operational Efficiency
Service Quality
Key KPIs
Total Bookings
Successful Bookings
Cancellation Rate
Total Revenue
Average Booking Value
Average Ride Distance
Customer Ratings
Driver Ratings
V_TAT
C_TAT
SQL Analysis

Business requirements were addressed using SQL queries such as:

Successful bookings analysis
Average ride distance by vehicle type
Customer cancellation count
Top customers by ride volume
Driver cancellation analysis
Vehicle-wise rating analysis
UPI payment analysis
Successful booking value calculation
Incomplete ride investigation
Example Query
SQL
SELECT Vehicle_Type,
AVG(Ride_Distance) AS Avg_Distance
FROM Booking
GROUP BY Vehicle_Type;
Power BI Dashboard

The dashboard contains 5 reporting pages:

Overall Analysis
Total Bookings: 40.54K
Successful Bookings: 25.21K
Total Booking Value: ₹13.76M
Ride Volume Trend
Booking Status Distribution
Vehicle Type Analysis
Booking Value by Vehicle Type
Distance Travelled
Vehicle Performance Comparison
Revenue Analysis
Revenue Trends
Revenue by Payment Method
Customer Revenue Contribution
Cancellation Analysis
Customer Cancellation Reasons
Driver Cancellation Reasons
Cancellation Percentage
Ratings Analysis
Driver Ratings
Customer Ratings
Vehicle-wise Service Quality
Key Findings
40.54K total bookings generated ₹13.76M booking value.
25.21K rides were successfully completed.
Overall cancellation rate reached 10.96%.
High-performing vehicle categories contributed stronger revenue.
Customer and driver ratings averaged around 4.0, indicating generally satisfactory service quality.
Digital payment methods generated the majority of booking value.
Peak demand periods revealed opportunities for better pricing and driver allocation.
Business Insights
Reducing cancellation rates can significantly increase realized revenue.
Vehicle allocation can be optimized during high-demand periods.
Driver availability directly impacts booking success rates.
Improving lower-rated service categories can strengthen customer retention.
Popular payment methods provide opportunities for reward-based campaigns.
Recommendations
Analyze major cancellation reasons and improve ride confirmation processes.
Increase driver availability during peak demand hours through incentives.
Optimize vehicle deployment using demand patterns.
Improve service quality in lower-rated vehicle categories.
Introduce loyalty rewards and cashback campaigns for preferred payment methods.
Leverage demand insights for dynamic pricing and targeted promotions.
Key Skills Demonstrated
SQL Querying
Data Cleaning & Validation
Data Analysis
Power BI Dashboard Development
DAX Measures
KPI Reporting
Business Intelligence
Data Visualization
Stakeholder Reporting
Executive Summary

This project analyzed 40.54K ride bookings and ₹13.76M in booking value to evaluate booking performance, revenue trends, cancellations, vehicle utilization, customer experience, and operational efficiency. The findings highlight significant opportunities in cancellation reduction, driver utilization, vehicle allocation, and customer retention, enabling data-driven business decision-making.

# Author

Shubham Kumar Jha
Aspiring Data Analyst | SQL | Power BI | Excel | Tableau | Python
