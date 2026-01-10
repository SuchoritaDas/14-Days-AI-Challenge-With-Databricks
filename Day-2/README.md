# Day 02 – Working with Data Using Apache Spark

On Day 2 of the Databricks 14-Day AI Challenge, I started working with real data using Apache Spark and PySpark inside Databricks.

This day was about understanding how large datasets are loaded, explored, and analyzed in a modern data platform.


---

What I worked on

I used a real e-commerce dataset that contains information about:

product views

cart additions

purchases

prices

brands

This type of data is similar to what online shopping companies use to understand customer behavior.

## What I did step-by-step


1️⃣ Loaded the dataset into Databricks

I uploaded a CSV file into Databricks and read it into a Spark DataFrame.
A DataFrame is like a big table that Spark can process very fast.


2️⃣ Checked the structure of the data

Using printSchema(), I explored:

column names

data types (price, brand, event type, etc.)


This helped me understand what kind of information the dataset contains.


3️⃣ Explored the data using PySpark

I used PySpark commands such as:

select() to choose specific columns

filter() to apply conditions

groupBy() to group similar values

orderBy() to sort results


These are the same tools analysts use to explore business data.


4️⃣ Analyzed user activity

I counted how many times different events occurred:

product views

cart additions

purchases

This shows how customers move from browsing to buying.



5️⃣ Filtered products by price

I filtered products where the price was greater than 100.
This is useful when companies want to focus on higher-value products.


6️⃣ Found top brands

I grouped the data by brand and counted how often each brand appeared.
Then I sorted the results to find the most popular brands based on user activity.

This is the type of insight businesses use to decide:

which brands to promote

which products to stock more


## What I learned

How Apache Spark handles large datasets

How PySpark is used to analyze data

How raw customer actions (views, carts, purchases) can be turned into useful business insights

How analysts start finding patterns in big data


Key takeaway

Day 2 showed me how data moves from being just a file into something that can answer real business questions.
With Spark and Databricks, large datasets can be explored quickly and turned into meaningful insights.


