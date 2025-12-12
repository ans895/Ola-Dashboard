# Ola-Dashboard

OLA Cab Operations & Cancellation Analysis Dashboard
This project is an end-to-end data analysis solution for a hypothetical cab service (based on OLA) built using SQL for data preparation and Power BI for visualization and insightful reporting.

Project Overview & Goal
The primary objective of this dashboard is to monitor key performance indicators (KPIs) and deeply analyze the reasons behind ride cancellations, driver performance, and revenue streams over a one-month period (July 2024).

1. The analysis focuses on answering critical business questions like:

2. What is the true booking success rate across different vehicle types?

3. What are the major controllable reasons for ride cancellations (customer vs. driver)?

4. How does the revenue split look across various payment methods?


 Technology Stack
 
 Component                              Tool/Language                                    UseCase
 Data PreparationSQL                  SQL (or Power Query M)                         Cleaning, transformation, and shaping raw booking and performance data.
Calculations & Logic	          DAX (Data Analysis Expressions)	      Creating complex measures like Success Booking Rate, Average Distance per Vehicle Type, and Total Booking 
Visualization	                     Power BI Service	                 Building interactive reports and dashboards for executive review.

Key Features & Insights
The dashboard is structured into four main pages: Overall, Vehicle Type, Revenue, and Cancellation.

1. Cancellation Analysis (High-Impact Area)
Driver vs. Customer Cancellation Split: The report segregates cancellations to pinpoint accountability.

Insight Example: Identified that 35% of driver cancellations were due to "Less than permitted time," indicating a potential issue with the assignment algorithm or expected turnaround time.

KPI Tracking: Tracks Total Bookings (103K+), Success Bookings, and Total Cancelled Bookings (28K+).

2. Vehicle Performance
Compares success booking value, success rate, and average distance across all vehicle types (Prime Sedan, SUV, Auto, E-Bike).

Insight Example: Noted that Auto bookings had a significantly lower average distance (approx. 10K) compared to Prime vehicles (approx. 25K), confirming its usage primarily for short-distance trips.

3. Revenue & Payment
Analyzes revenue breakdown by payment method (Cash, UPI, Credit Card).

Identifies Top 5 Customers based on booking volume for potential loyalty program targeting.

🔗 How to View the Dashboard
Download Source File: The full Power BI model can be downloaded using the Ola project.pbit file.

Screenshots
overall.png  https://github.com/ans895/Ola-Dashboard/blob/main/overall.png
vehicle.png  https://github.com/ans895/Ola-Dashboard/blob/main/vehicle.png
revenue.png  https://github.com/ans895/Ola-Dashboard/blob/main/revnue.png
canceld.png  https://github.com/ans895/Ola-Dashboard/blob/main/cancelld.png
rating.png   https://github.com/ans895/Ola-Dashboard/blob/main/rating.png
