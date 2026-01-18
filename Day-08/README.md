# Day 8 – Unity Catalog & Data Governance
This folder contains my work for Day 8 of the Databricks 14 Days AI Challenge, where the focus was on data governance, access control, and catalog management using Unity Catalog.
In real organizations, data is not just about processing — it is also about who can access what, how data is structured, and how changes are tracked. This day helped me understand how companies manage data safely at scale.
## What I learned
Unity Catalog provides a centralized way to manage data access and structure across Databricks.
Key concepts covered:
Catalog → Schema → Table hierarchy
Role-based access control using GRANT and REVOKE
Difference between managed tables and external tables
Data lineage and traceability
Secure data sharing using views
## What I implemented
I created a complete governance setup for an e-commerce dataset:
Created a catalog for the project
Created schemas for Bronze, Silver, and Gold layers
Registered Delta tables inside each schema
Applied permissions so different teams have different access levels
Created views to expose only approved business data
This mirrors how real data teams separate raw data from business-ready data while maintaining security.
Example structure
Catalog: ecommerce
Schemas: bronze, silver, gold
Tables:
Bronze → raw event data
Silver → cleaned and validated data
Gold → aggregated business metrics
## Why this matters
Without governance:
Anyone can access sensitive data
Changes can break dashboards
Compliance becomes impossible
Unity Catalog solves this by enforcing structure, permissions, and visibility across the platform.

Each day focuses on building real, hands-on data engineering skills using Databricks.
