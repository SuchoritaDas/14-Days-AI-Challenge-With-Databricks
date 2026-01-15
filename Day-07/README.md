# Day 07 – Workflows & Job Orchestration
On Day 7 of the Databricks 14-Day AI Challenge, I learned how data pipelines are automated and orchestrated in real production systems.
Until now, I was running notebooks manually.
Today, I turned them into a fully automated data pipeline using Databricks Jobs and Workflows.
This is how companies run data pipelines every day without clicking anything.
## What this day is about
Modern data platforms don’t rely on people to run notebooks.
They use workflows that execute tasks in a fixed order, handle failures, and run on schedules.
That is exactly what I built today.
## What I implemented
I created a multi-task Databricks Job that runs my Medallion Architecture pipeline:
Bronze → Silver → Gold
Each layer runs only when the previous one finishes successfully.
## What I built
I added parameter widgets to my notebooks so they can accept:
Source path
Layer type (bronze, silver, gold)
Then I used those parameters inside the notebooks so the same code can run for different layers.
Job Orchestration
I created a Databricks Job with three tasks:
First task runs the Bronze layer
Second task runs the Silver layer (depends on Bronze)
Third task runs the Gold layer (depends on Silver)
## This ensures:
Data flows in the correct order
No layer runs before its input is ready
Automation
I scheduled the job so the entire pipeline runs automatically every day.
This means the data lake updates itself without any manual effort.
Why this matters
This is how real data engineering works:
Pipelines run on schedules
Tasks depend on each other
Failures are tracked
Data stays fresh and reliable
Day 7 turned my notebooks into a real production-ready data pipeline.
Part of a sponsored learning challenge
This work is part of the Databricks 14-Day AI Challenge
