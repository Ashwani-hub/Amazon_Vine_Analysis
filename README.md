# Amazon_Vine_Analysis
## Overview
Use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 
Using PySpark determine if there is any bias toward favorable reviews from Vine members in the database
## Resources
Data Source: Amazon Review datasets, Video Games Review dataset
Software: Google Colab Notebook, PostgreSQL 12.8-1, pgAdmin4 4, AWS
## Analysis Results
### Deliverable 1
Video Games Review Dataset was analyzed and 4 tables were created in the database
Dataset was tranformed into four DataFrames to match schema in pgAdmin tables:
Snapshots for all 4 tables from pgAdmin uploaded into the Resources folder.
### Deliverable 2

### Results
### Total number of reviews
Total Number of paid reviews: 94
Total Number of unpaid reviews: 40471

### Total number of 5-star reviews
Total number of paid 5-star reviews: 48
Total number of unpaid 5-star reviews: 15663

### Percentage of 5-star reviews
Percentage of paid reviews: 51.0%
Percentage of unpaid reviews: 38.7%

## Summary
51% of the reviews in the Vine program were 5 stars reviews where as the percentage in the non-Vine reviews were only 39%
Based on the percentage summary, we can conclude that there is a positivity bias for reviews in the Vine program.

Further statistical distribution of star rating may provide additional support to the data analysis



              
