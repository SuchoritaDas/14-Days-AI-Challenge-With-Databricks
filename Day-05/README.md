# Day 05 – Delta Lake Advanced (Time Travel, MERGE & Optimization)
On Day 5 of the Databricks 14-Day AI Challenge, I worked with advanced Delta Lake features that are used in real production data systems.
This day focused on how data is updated, tracked, optimized, and cleaned in modern data platforms.
## What I worked on
I used Delta Lake tables to simulate how real businesses manage changing data over time.
## What I did step by step
1️⃣ Implemented MERGE (Incremental Updates)
I used MERGE to update existing records and insert new ones in the Delta table.
This is called an upsert and is commonly used when new data arrives daily.
2️⃣ Queried historical versions (Time Travel)
I used Delta Lake Time Travel to read:
previous versions of a table
data as it existed on a specific date or time
This helps in:
debugging data issues
auditing changes
recovering lost data
3️⃣ Optimized the tables
I used:
OPTIMIZE to compact small files
ZORDER to organize data for faster queries
This improves performance when working with large datasets.
4️⃣ Cleaned old data using VACUUM
I used VACUUM to remove old and unused files from storage.
This keeps the data lake clean and reduces storage cost.
## What I learned
How Delta Lake supports version history
How MERGE handles incremental data loads
How OPTIMIZE and ZORDER improve performance
How VACUUM helps manage storage
## Key takeaway
Day 5 showed me how data is not just analyzed, but maintained like a living system — always changing, always improving, and always protected.
