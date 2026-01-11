# Day 03 – PySpark Transformations Deep Dive
On Day 3 of the Databricks 14-Day AI Challenge, I worked on advanced PySpark transformations to understand how real-world data pipelines are built.
This day focused on going beyond simple filtering and grouping, and learning how data is combined, ranked, and transformed into new insights.
## What I worked on
I used the full e-commerce dataset of 2019's October and November and performed multiple transformations to analyze customer behavior and product performance.
## What I did step by step
1️⃣ Loaded the full dataset
I worked with the complete e-commerce data inside Databricks using PySpark DataFrames.
2️⃣ Performed joins
I used joins (inner, left, right, and outer) to combine related data tables.
This helps bring product, user, and event data together into a single view — just like real analytics systems do.
3️⃣ Used window functions
I applied window functions to calculate:
running totals
rankings
performance comparisons over time
This is useful for understanding trends like:
top-selling products
best-performing brands
customer activity over time
4️⃣ Created derived features
I created new columns from existing data to make analysis more meaningful, such as revenue, rankings, and grouped values.
These are called derived features and are used heavily in real business reporting and machine learning.
## What I learned
How PySpark handles large data better than Pandas
How joins combine multiple datasets into one analysis view
How window functions help track trends and rankings
How raw data can be transformed into business-ready metrics
## Key takeaway
Day 3 showed me how data is engineered, not just explored.
By joining tables, creating new columns, and using window functions, raw data becomes something businesses can actually make decisions from.
