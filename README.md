# Movies-ETL

## Project Overview
In this analysis, we started with data pipline process which means Extract, Transform, and load or ETL. ETL is the process of moving information between
databases. For example Google and Amazon are constantly moving data around to different locations to improve performance. ETL is a core concept in data engineering 
insures the data is consistant and maintains integrated because without consistant robust data any forrm of analysis is impossible.
The ETL process can also create data store, that perform more efficiently reducing the time. We will be using pandas and Python to perform our data wrangling 
and PostgresSQL to store our finished data. 

This project is done as follows:
   - Create an automated pipeline that takes in new data
   - Perform the appropriate transformations
   - Load the data into existing table and create the Movie Database. 



## Resources
- Data Sources: movies_metadata.csv, ratings.csv, wikipedia-movies.json
- Software: [Jupyter Notebook](https://www.anaconda.com/products/individual), [PostgresSQL](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)
- Module: pandas, numpy, json, re, create_engine, db_password, time  


## Summary

Using the knowledge of Python, Pandas, the ETL process, to achieve the following goals: 
- Write a function that reads in the three data files and creates three separate DataFrames.
- Extract and transform the Wikipedia data so we can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates,   use a try-except block to catch errors.
- Extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. 
- Merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. 
- Merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.
- use PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.

