# 🚖 Taxi Trip Data Analysis (SQL Project)

## 📌 Project Overview
This project demonstrates SQL techniques used by analysts to explore, clean, and analyze **NYC-style taxi trip data**.  
It focuses on **revenue analysis, customer behavior, driver performance, and route optimization** to support data-driven business decisions.

- **Project Title:** Taxi Trip Data Analysis  
- **Level:** Beginner to Intermediate  
- **Database:** `p2_taxi_trip_db`  
- **Author:** Dhruv (IED/10017/22)  

---

## 🎯 Objectives
1. Set up a Taxi Trip database and populate it with data.  
2. Perform **data cleaning & preprocessing** to handle missing values, outliers, and inconsistent records.  
3. Conduct **exploratory data analysis (EDA)** to understand customer, driver, and trip patterns.  
4. Answer **business-driven questions** through SQL queries.  
5. Derive **actionable insights** for decision-making.  

---

## 🗂 Database Structure
- **taxi_trips**  
  - trip_id  
  - pickup_datetime  
  - dropoff_datetime  
  - passenger_count  
  - trip_distance  
  - pickup_zone  
  - dropoff_zone  
  - fare_amount  
  - tip_amount  
  - total_amount  
  - payment_type  
  - driver_id  

---

## 🛠 Data Preprocessing
- Counted total records.  
- Checked for missing/null values.  
- Removed invalid records (negative fares, zero passengers, impossible distances).  
- Detected outliers (extremely high fares or distances).  
- Ensured data consistency (`fare + tip ≈ total`).  

---

## 🔍 Key Business Analysis Questions
1. What is the total number of trips, drivers, and unique zones?  
2. How does monthly revenue trend over time?  
3. What are the peak booking hours?  
4. Who are the **top 5 earning drivers**?  
5. What is the average trip distance per driver?  
6. Which are the most popular pickup zones?  
7. What is the passenger count distribution?  
8. What is the revenue breakdown by **payment type**?  
9. What is the average tip percentage by payment method?  
10. Which are the **top 5 busiest routes**?  
11. Which are the **top 3 highest revenue routes**?  
12. How does revenue compare between **weekdays and weekends**?  
13. What were trips and revenue on **New Year’s Eve**?  

*(See the [Questions PDF](Taxi_SQL_Project_Questions.pdf) for detailed list.)*

---

## 📊 Findings
- **Peak hours**: Evenings showed maximum demand.  
- **Top drivers**: A small group of drivers contributed the most earnings.  
- **Payment preference**: Majority of trips paid via credit card.  
- **Zones**: Downtown and airports generated the highest trips and revenue.  
- **Seasonality**: December (holiday season) had a significant revenue spike.  

---

## 📂 Project Files
- `database_setup.sql` → SQL script to create database & tables.  
- `data_cleaning.sql` → SQL queries for preprocessing.  
- `analysis_queries.sql` → SQL queries answering business questions.  
- `Taxi_SQL_Project_Questions.pdf` → PDF of project questions.  
- `sample_nyc_taxi.csv` → Sample dataset for analysis.  

---

## 🚀 How to Use
1. Clone this repository.  
2. Import the dataset (`sample_nyc_taxi.csv`) into your SQL database.  
3. Run the scripts in order:  
   - `database_setup.sql`  
   - `data_cleaning.sql`  
   - `analysis_queries.sql`  
4. Explore and modify queries as needed.  

---

## 📌 Conclusion
This project serves as a **portfolio-ready end-to-end SQL case study**.  
It demonstrates strong **SQL skills, analytical thinking, and business insight generation**.  

---
👨‍💻 **Author: Dhruv (IED/10017/22)**  
