# Day 11: Statistical Analysis & ML Preparation
This folder contains my work for Day 11 of the Databricks 14 Days AI Challenge, focused on building strong statistical foundations and preparing data for machine learning.
## What this day is about
Before training any ML model, it’s important to understand the data deeply. This day focuses on statistics, hypothesis thinking, and feature engineering using Spark.
## What I implemented
1. Descriptive Statistics
I explored basic statistical summaries (count, mean, min, max) to understand how numerical variables behave.
2. Weekday vs Weekend Analysis
I created a derived column to identify weekends and compared event behavior between weekdays and weekends to see if user activity patterns change.
3. Correlation Analysis
Checked correlations between important variables like price and conversion-related metrics to understand relationships in the data.
4. Feature Engineering for ML
Created new features that are commonly used in machine learning:
Hour of the event
Day of the week
Log-transformed price
Time since first interaction (user-level time feature)
These features help models capture time-based behavior and scale numerical values properly.
## Tools & Concepts Used
Apache Spark (PySpark)
Databricks notebooks
Descriptive statistics
Correlation analysis
Feature engineering
Window functions
## Why this matters
This day bridges analytics and machine learning.
Good features and statistical understanding directly improve model performance and explainability.
