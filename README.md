# Executive-Sales-Performance-Dashboard
A professional sales dashboard that turns complex hardware market data into clear charts to help a company track its money, growth, and customer trends

**📖 Project Overview**

This project takes raw sales data from a MySQL database (db_dump.sql) and turns it into useful business information. As a Senior Data Analyst, I focused on two main goals:
Revenue Growth: Tracking where the money comes from.
Customer Health: Understanding who the best customers are.


**🛠️ Tech Stack**

SQL: Used for cleaning data and joining tables.
HTML & Tailwind CSS: Used to build a clean, modern dashboard layout.
Chart.js: Used to create interactive and advanced charts.
Python (Pandas): Used for initial data exploration and currency normalization.


**🚀 Key Dashboards**

1. Executive Sales Dashboard
This dashboard gives a "big picture" view of the company.
Currency Normalization: The data had both INR and USD. I converted everything to INR for accurate totals.
Market Analysis: Shows which cities (like Delhi NCR) are leading in sales.
Yearly Trends: Tracks how sales jumped between 2017 and 2020.

2. Customer & Order Study
This section focuses on the people buying the products.
VIP Identification: Using SQL to find the top 5 spenders.
Loyalty Tracking: Finding customers who buy frequently (High-Frequency).
Zone Distribution: Seeing which part of India (North, South, Central) has the most unique customers.


**💡 Senior Analyst Insights**

Market Risk: 60% of revenue comes from Delhi NCR. The company should try to grow more in the South Zone to reduce risk.
Sales Spike: There was a 330% growth in 2018. We should study what happened that year to do it again.
Channel Opportunity: "Brick & Mortar" (physical stores) are the main sellers, but "E-commerce" is a big opportunity for future growth.


**📂 How to Run**

Database: Import the db_dump.sql file into your MySQL Workbench.
Dashboard: Open the pro_dashboard.html file in any web browser (Chrome, Safari, or Edge).
Analysis: Check the Customer_Analysis.sql file for the specific queries used for the VIP study.
