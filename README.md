# Hospital-Management-Data-Analysis-SQL-Project-
📌 Project Overview

My project is Hospital Management Data Analysis using SQL.The main goal of this project was to analyze hospital data and find useful insights that can help hospital management make better decisions.I worked with five tables: Patients, Doctors, Appointments, Billing, and Treatments.First, I checked the data for any problems, such as billing records with zero amounts and appointments with missing patient IDs. This helped ensure the data was accurate before analysis.

challenge : one of the biggest challenge was checking the data quality. Some records had missing values or invalid data, so I identified those records before starting the analysis. This helped me get accurate results.

This project focuses on analyzing a hospital management dataset to uncover key insights related to patients, doctors, appointments, treatments, and billing.

The goal is to perform end-to-end SQL analysis and generate actionable insights that can help improve hospital operations, revenue, and decision-making.

🎯 Objectives
Analyze patient demographics and behavior
Evaluate doctor performance and workload
Track appointment trends and cancellations
Identify revenue drivers and billing patterns
Provide business insights for operational efficiency
🗂️ Dataset Description

The dataset consists of multiple related tables:

Patients → patient details, gender, date of birth, insurance
Doctors → specialization, experience
Appointments → appointment date, status
Treatments → treatment type, cost
Billing → payment amount, method, status
🛠️ Tools & Technologies
SQL (MySQL)
Data Analysis
Relational Database Concepts
🔍 Key SQL Concepts Used
Joins (INNER JOIN, LEFT JOIN)
Aggregations (SUM, COUNT, AVG)
Window Functions (RANK(), ROW_NUMBER(), DENSE_RANK())
CASE Statements
Date Functions (DATEDIFF, TIMESTAMPDIFF)
Grouping & Filtering (GROUP BY, HAVING)
📊 Key Analysis & Queries
🟢 Basic Analysis
Total patients, doctors, appointments
Appointment status distribution
Monthly appointment trends
🟡 Intermediate Analysis
Patients by gender and insurance status
Doctor workload and specialization distribution
Top 10 high-value patients
🔵 Advanced Analysis
Revenue by treatment and payment method
Paid vs pending billing percentage
Ranking doctors based on revenue
Top treatments per month using window functions
Running revenue trend over time
