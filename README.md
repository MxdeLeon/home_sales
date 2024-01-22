# home_sales
Home sales data analysis using PySpark

Analysis is performed on home sales using a dataset containing sales data and home metrics including square footage, # of bed/bath rooms, view ratings, build date, etc...

Using PySpark, data is loaded into a data frame and a temporary table view is created.

Various queries are performed on the table to show average sale price by year, average sales price by home size and room count, etc...

Query speed optimization is explored using caches and parquet files.
