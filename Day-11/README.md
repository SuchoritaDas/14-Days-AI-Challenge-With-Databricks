# Day 11 – Statistical Analysis & ML Preparation
This notebook focuses on understanding data behavior and preparing it for machine learning, using real e-commerce event data on Databricks.
The goal of this day was not model building, but building strong analytical foundations that ML models depend on.
## What this notebook covers
1. Descriptive Statistics
Basic statistical summaries were calculated to understand how numeric fields like price behave across the dataset. This helps identify outliers, ranges, and data quality issues early.
2. Hypothesis Testing (Weekday vs Weekend)
User behavior was compared between weekdays and weekends to analyze whether engagement or conversion patterns change based on time. This simulates real business questions such as “Do weekends perform better?”
3. Correlation Analysis
Correlation was calculated between price and conversion rate to understand whether pricing impacts purchasing behavior and how strong that relationship is.
4. Feature Engineering for ML
New features were created from raw event data, including:
Hour of activity
Day of the week
Log-transformed price
Time since first user interaction
These features are essential inputs for machine learning models and advanced analytics.
## Why this day matters
Most ML failures happen due to poor data preparation, not poor models.
This day emphasizes:
Analytical thinking before modeling
Business-driven feature creation
Clean, explainable transformations
## Tools & Technologies Used
Databricks
Apache Spark (PySpark & Spark SQL)
Window functions
Statistical functions
