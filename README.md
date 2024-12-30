# Ola_Data_Analytics_Project

SQL Questions:
Retrieve all successful bookings:
Find the average ride distance for each vehicle type:
Get the total number of cancelled rides by customers:
List the top 5 customers who booked the highest number of rides:
Get the number of rides cancelled by drivers due to personal and car-related issues:
Find the maximum and minimum driver ratings for Prime Sedan bookings:
Retrieve all rides where payment was made using UPI:
Find the average customer rating per vehicle type:
Calculate the total booking value of rides completed successfully:
List all incomplete rides along with the reason:


Power BI Questions:

Ride Volume Over Time
Booking Status Breakdown
Top 5 Vehicle Types by Ride Distance
Average Customer Ratings by Vehicle Type
Cancelled Rides Reasons
Revenue by Payment Method
Top 5 Customers by Total Booking Value
Ride Distance Distribution Per Day
Driver Ratings Distribution
Customer vs. Driver Ratings

1. Retrieve all successful bookings:
Create view sucessful_bookings As
SELECT * FROM bookings
WHERE Booking_Status = 'Success';

SELECT * FROM successful_bookings;

