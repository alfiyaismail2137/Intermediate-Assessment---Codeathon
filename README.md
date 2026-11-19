# Logistics Transportation

Problem Statement:
 A logistics company wants to analyze its fleet performance in terms of on-time deliveries, fuel efficiency, and cost per mile.
Dataset: Logistic Dataset Link
Dataset Fields: 
●	Trip ID, Vehicle ID, Driver ID, Origin, Destination, Distance (km), Fuel Consumed (liters), Delivery Status (On-Time/Late), Delivery Date.
●	Vehicle Master: Vehicle ID, Vehicle Type, Capacity, Maintenance Cost.
Project steps and objective:
1.	Data Cleaning & Modeling: (5marks)
○	Fix missing fuel consumption values (use avg. per vehicle type).
○	Relate Trips with Vehicle Master.
2.	DAX Measures:  (5marks)
○	Fuel Efficiency = Distance / Fuel Consumed
○	On-Time Delivery % = On-Time Trips / Total Trips
○	Cost per km = (Fuel Cost + Maintenance Cost) / Distance
3.	Visualization:  (5marks)
○	Bar chart: On-Time Delivery % by Route.
○	Line chart: Fuel Efficiency trend by month.
○	KPI cards: Avg. Delivery Time, Cost per km.
○	Map visual: Delivery performance by route (Origin → Destination).
Expected Output: A transport operations dashboard to optimize routes and fleet usage.
