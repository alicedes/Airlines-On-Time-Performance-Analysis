# Airlines On-Time Performance Analysis

## Introduction

This project aims to provide insights into airlines' on-time performance using a dataset sourced from the US Department of Transportation, Bureau of Transportation Statistics. The analysis will address five key questions related to airline carrier performance. https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ 

## Data Source

The dataset used for this analysis is sourced from the US Department of Transportation, Bureau of Transportation Statistics. The dataset provides information on flight details, including carrier information, flight timings, delays, and more.

## Questions Addressed

### 1. Ranking Airlines by Year

- What are the airlines with the most flights by year?
- Are there any trends worth noting?

### 2. Best Time to Fly to Minimize Delays

- When is the best time of day/day of week/time of year to fly to minimize delays?

### 3. Impact of Aircraft Age on Delays

- Do older planes suffer more delays?

### 4. Changes in Passenger Traffic Over Time

- How does the number of people flying between different locations change over time?

### 5. Percentage of Flights Delayed by Weather per Airport

- What percentage of flights are delayed by weather per airport?

## Data Storage and Analysis Setup

- Upload the dataset to an AWS S3 bucket for storage.
- Set up an AWS RDS instance with the appropriate SQL database (e.g., MySQL, PostgreSQL).
- Use AWS Glue for data transformation and ETL processes if necessary.
- Connect to the SQL database using an SQL client such as MySQL Workbench or pgAdmin.

## SQL Queries

- Write SQL queries to perform the analysis and address the five key questions.
- Utilize SQL functions, joins, and aggregations to extract meaningful insights from the dataset.
- Document the SQL queries used for each analysis task.

## AWS Setup Instructions

1. Set up an AWS account if you haven't already.
2. Create an S3 bucket for data storage.
3. Launch an RDS instance with the desired SQL database engine.
4. Connect to the RDS instance and create the necessary tables for storing the dataset.
5. Grant appropriate permissions to access the S3 bucket and RDS instance.
6. Optionally, configure AWS Glue for data transformation and ETL processes.

## Conclusion

The analysis of airline on-time performance using SQL on AWS provides valuable insights into carrier performance, flight timings, and factors influencing delays. By addressing the five key questions, this report aims to assist stakeholders in understanding trends and making informed decisions related to air travel.

