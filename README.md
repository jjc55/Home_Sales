# Home_Sales

Module 22 Challenge on Big Data

### Overview
In this challenge, I used SparkSQL to analyze home sales data to find the following:
1. the average price for a 4-bedroom house by year, 
2. the average price for 3 bedrooms and 3 bathrooms home by year, 
3. the average price for a home with 3 bedrooms, 3 bathrooms, 2 floors, and is >= 2,000 square feet by year, and
4. the "view" rating for homes costing >= $350,000.

I also used PySpark to create temporary views, partition data, as well as cache and uncache a temporary table.  

### Analysis 
Creating a “view” with uncached data took 1.55 seconds. Creating a “view” with cached data took 1.02 seconds. Creating a “view” with parquet formatted data took 0.70 seconds. Overall, parquet formatted data took the shortest amount of time, while uncached data took the longest amount of time. The time it took for cached data to complete the query was in between parquet formatted and uncached data. 
