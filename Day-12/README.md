# Phase 4: AI & Machine Learning (Days 12–14)
On Day 12 of the Databricks 14 Days AI Challenge, I focused on understanding how MLflow is used to track, manage, and compare machine learning experiments in a real analytics environment.
This day connects analytics data with machine learning workflows and shows how models are handled beyond just training.
## 🔍 What I Learned
MLflow is an open-source platform that helps track experiments, store models, and compare results.
Key concepts covered today:
MLflow components (experiments, runs, metrics, models)
Experiment tracking
Logging parameters and metrics
Viewing and comparing runs using the MLflow UI
## 🛠 What I Implemented
For hands-on practice, I built a simple regression model using data from the Gold layer.
-- Steps followed:
Loaded curated analytics data from Databricks tables
Prepared features and target variables
Split data into training and test sets
Trained a Linear Regression model
Logged model details using MLflow
📊 MLflow Tracking Details
During model training, I logged:
Model type (Linear Regression)
Train–test split size
Model performance using R² score
The trained model artifact
All runs were tracked automatically and visualized inside the MLflow UI, making it easy to compare different experiments.
## 📈 Why This Matters
This workflow is important because:
Experiments become reproducible
Model performance is clearly tracked
Teams can compare models easily
Models can move smoothly from experimentation to production
It bridges the gap between data engineering and machine learning.
## 🧠 Key Takeaway
Day 12 helped me understand that building a model is only part of the job.
Tracking, comparing, and managing experiments is what makes machine learning reliable and scalable in real companies.
