# Bike sales sample data
## 1. Overview 

This is my data analytics exercise to practice writing SQL queries and visualizing in Tableau.

Scenario: A bike selling company wants to create a dashboard for bike sales from 2016 to 2018.

Tool used: SQL and Tableau

## 2. Data
* The data is a sample dataset come from this <a href="https://www.sqlservertutorial.net/load-sample-database">website</a> (I will upload the dataset to this repository).
* I use postgreSQL to host a local database called 'bike_sales'.
* The dataset has two schema: "sales" and "production".
  * In the "production" schema, there are 4 tables: categories, brands, products, stocks.
  * In the "sales" schema there are 5 tables: customers, stores, staffs, orders, order_items.

## 3. Writing queries and creating visualization.
* First, I write a <a href="https://github.com/Longnh-github/Bike-sales/blob/main/bike_sales_cleaned/bike_sales_cleaned.sql">SQL query</a> to join multiple tables' properties together, and export the data into a csv file.
* Second, I import the data in csv file into Tableau and create this <a href="https://public.tableau.com/app/profile/long7032/viz/Bikesales_16763818255090/ReportDashboard">visualization</a>.
