# Zoomride-Data-Analysis-Project
ZoomRide is a company that sells rides in cars and bikes, like Uber or Bolt. It works in 6 cities: Lagos, Abuja, Port Harcourt, Nairobi, Accra and Kampala.

## Project Overview

ZoomRide is a ride-hailing business operating across multiple cities. This project uses SQL to analyze trip records, customer activity, revenue performance, and vehicle-type performance.

The objective is to answer key business questions, identify data-quality issues, and generate actionable insights that can help management make informed business decisions.

##  Business Questions and Answers

This project explores the following business questions:

1. How many trips are recorded in the database?
2. What are the five longest completed trips?
3. How many trips were recorded in each city?
4. Are there duplicate trips or completed trips with missing fares?
5. How can inconsistent city names be standardized?
6. Which cities generate the highest revenue?
7. Which months generate the highest revenue?
8. Which vehicle types generate the most revenue?
9. Which customers have never booked a trip?
10. Who are the top three customers by total spending on completed trips?

### Key Answers

- **Leading city by revenue:** Lagos generated 218,890 from 93 completed trips.
- **Highest-revenue month:** December 2025 generated 66,980 from 31 completed trips.
- **Top vehicle type by revenue:** Economy generated 262,550 from 121 completed trips.
- **Highest-spending customer:** Chioma Nwosu spent 38,950 across 21 completed trips.

*Note: Revenue figures are presented without a currency symbol because the dataset does not specify the currency.*

## 3. Key Performance Indicators (KPIs)

The analysis focuses on the following metrics:

- Total number of trips
- Number of completed trips
- Total revenue from completed trips
- Average fare per completed trip
- Trip count and revenue by city
- Monthly trip count and revenue
- Revenue by vehicle type
- Top customers by total spend
- Number of duplicate trip records
- Completed trips with missing fares
- Customers who have never booked a trip

## 4. Tools Used

- **SQL:** Data exploration, filtering, aggregation, joins, sorting, and data cleaning.
- **Relational Database:** Customer, driver, and trip records.

### SQL Techniques Applied

- `SELECT`, `WHERE`, and `ORDER BY`
- Aggregate functions: `COUNT()`, `SUM()`, and `AVG()`
- `GROUP BY` and `HAVING`
- `INNER JOIN` and `LEFT JOIN`
- `IS NULL` for identifying missing values
- `UPDATE` and `DELETE` for data cleaning
- `DATE_FORMAT()` for monthly revenue analysis

## 5. Analysis Overview

This is a SQL-based analysis project; no dashboard was created.

The SQL queries were used to examine trip activity, compare revenue across cities and months, evaluate vehicle-type performance, identify high-spending customers, and investigate data-quality issues.

The results were used to develop business recommendations based on trip demand and revenue performance.

## 6. Key Insights

### City Performance

Lagos generated the highest revenue at 218,890 from 93 completed trips, making it the leading city by completed-trip revenue in the analysis.

### Monthly Performance

December 2025 was the strongest month, generating 66,980 from 31 completed trips. April 2026 recorded the lowest monthly revenue at 21,160 from 14 completed trips.

### Vehicle-Type Performance

Economy vehicles generated the highest revenue at 262,550 from 121 completed trips. Comfort vehicles followed with 239,050 from 76 trips, while Bikes generated 66,870 from 51 trips.

### Customer Spending

The top three customers by total spending on completed trips were:

1. Chioma Nwosu — 38,950 across 21 trips.
2. Tunde Bakare — 37,610 across 13 trips.
3. Zainab Garba — 35,380 across 15 trips.

### Data Quality Findings

The analysis identified inconsistent city names, including spelling errors, abbreviations, and formatting differences. These were standardized to improve reporting consistency.

Two duplicate trip records were also identified and removed. Trip records with missing fares were investigated separately and were not assigned invented fare values.

## 7. Files in the Repository

- `README.md` — Project overview, business questions, KPIs, findings, and conclusion.
- `zoomride_esther.sql` — SQL queries used for data exploration, cleaning, and analysis.

*Ensure the SQL filename above matches the actual filename in your GitHub repository.*

## 8. Conclusion

This project demonstrates  SQL can be used to clean data, investigate data-quality issues, and analyze business performance. Lagos led the cities in completed-trip revenue, December 2025 recorded the highest monthly revenue, and Economy vehicles generated the most revenue among the vehicle categories analyzed.

Based on these findings, Lagos is a strong candidate for further investment evaluation. Before committing resources, ZoomRide should also compare operating costs, profit margins, driver availability, and future demand to determine which city offers the best return on investment.
