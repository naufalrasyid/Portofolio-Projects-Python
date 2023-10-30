# About Dataset
Stores:
Store: The store number. Range from 1–45.
Type: Three types of stores ‘A’, ‘B’ or ‘C’.
Size: Sets the size of a Store would be calculated by the no. of products available in the particular store ranging from 34,000 to 210,000.
primary key is Store

Sales:
-Date: The date of the week where this observation was taken.
-Weekly_Sales: The sales recorded during that Week.
-Store: The store which observation in recorded 1–45
-Dept: One of 1–99 that shows the department.
-IsHoliday: Boolean value representing a holiday week or not.

primary key is a combination of (Store,Dept,Date).

Features:
-Temperature: Temperature of the region during that week.
-Fuel_Price: Fuel Price in that region during that week.
-MarkDown1:5 : Represents the Type of markdown and what quantity was available during that week.
-CPI: Consumer Price Index during that week.
-Unemployment: The unemployment rate during that week in the region of the store.

