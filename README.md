# Sales Insights Data Analysis in Power BI

![image](https://github.com/user-attachments/assets/de3adede-ff5c-47fa-8cb1-b14a4f39c2f7)


Project Overview: 
This Power BI project was developed to assist AtliQ Hardware, a fictional computer hardware supplier, in identifying key sales trends and overcoming declining revenue. By leveraging Power BI’s data visualization capabilities, the project provides actionable insights that enable data-driven decisions for business growth.

Project Goals: 
Diagnose the causes behind declining sales trends.
Visualize sales performance across time and product categories.
Deliver a dynamic dashboard that supports real-time data exploration and decision-making.
Approach

1. Data Setup & Exploration
Server Configuration & Data Import:
Set up a MySQL server and imported sales data for analysis.
SQL Queries for Insight Discovery:
Ran key SQL queries to analyze data integrity and structure, uncovering:
🚩 Negative values in the transactions table that required resolution.
💱 Dual currency transactions (INR and USD) to be standardized into INR.

3. Data Integration with Power BI
ETL Process (Extract, Transform, Load):
Connected MySQL directly to Power BI, ensuring a smooth data import pipeline.
Data Transformation Highlights:
Cleared blank entries to maintain data cleanliness.
Removed negative sales values after validation in MySQL.
Standardized currency by converting USD to INR using a custom column.
Applied all transformations seamlessly using Power BI's Close & Apply feature.

4. Data Analysis & Visualization Preparation
Used inner joins to link transactions with date data, providing time-based revenue insights.
Calculated annual and total revenue, establishing a robust foundation for visual storytelling.


Key Insights
Identified inconsistencies in transaction data, including negative values and dual currencies, and resolved them for accurate reporting.
Established a clean, integrated dataset ready for dynamic, interactive visualizations in Power BI.
Let’s Collaborate!

I welcome feedback and collaboration from data analytics enthusiasts. Feel free to share your Power BI experiences, tips on ETL optimization, or best practices for building impactful dashboards!

Let me know if you'd like further adjustments or additions!
