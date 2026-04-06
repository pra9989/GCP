module4-preparing-and-using-data-for-analysis\
1) Preparing and using cymbal Retails data for analysis \
2) Diagnostic questions \
3) Review and study planning \
   Helping Cymbal Retail use data to make decisions \
   Cymbal Retail wants to use data make informed decisions \
   Systems need to be flexible, agile and customizable \
   You need to help support the business in using data \
SHARING   DATA AND REPORTING \
  partner specific reports and accounts \
 Limited data access for industry and goverement bodies \
SUPPORTING MACHINE LEARNING ADVANCEMENTS \
CYmbal retail is using fine-tuned predictions to estimate   demand and individual customer behaviour \
you need to help process data to make it usable for building machine learning models \

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>> 
our score: 20% Passing score: 80% \
Unfortunately, you need at least a 80% to pass this assessment. Not to worry though, review your answers and try again. \
close \
1. \
 \
You need to optimize the performance of queries in BigQuery. Your tables are not partitioned or clustered. What optimization technique can you use? \
Filter data as late as possible. \
close \
Use the LIMIT clause to reduce the data read. \
Batch your updates and inserts. \
Perform self-joins on data. \
Incorrect. A limit clause is applied at the end of the query, which does not make it performant. \
close \
2. \
 \
You built machine learning (ML) models based on your own data. In production, the ML models are not giving satisfactory results. When you examine the data, it appears that the existing data is not sufficiently representing the business goals. You need to create a more accurate machine learning model. What should you do? \
Perform feature engineering, and use domain knowledge to enhance the column data. \
Perform L2 regularization. \
Train the model with more of similar data. \
close \
Train the model with the same data, but use more epochs. \
Incorrect. Repeating training for longer with the same data might not improve the model. \
close \
3. \
 \
You have analytics data stored in BigQuery. You need an efficient way to compute values across a group of rows and return a single result for each row. What should you do? \
close \
Use a UDF (user-defined function). \
Use an aggregate function. \
Use BigQuery ML. \
Use a window function with an OVER clause. \
Incorrect. Using a UDF function entails extra work; therefore, it is not the most efficient solution. \
close \
4. \
 \
Your company uses Google Workspace and your leadership team is familiar with its business apps and collaboration tools. They want a cost-effective solution that uses their existing knowledge to evaluate, analyze, filter, and visualize data that is stored in BigQuery. What should you do to create a solution for the leadership team? \
Configure Connected Sheets. \
close \
Create models in Looker. \
Configure Tableau. \
Configure Looker Studio. \
Incorrect. Using Looker requires additional training for the team and incurs additional cost. \
check \
5. \
 \
You repeatedly run the same queries by joining multiple tables. The original tables change about ten times per day. You want an optimized querying approach. Which feature should you use? \
check \
Materialized views \
Partitions \
Views \
Federated queries \
Correct. Materialized views will improve query performance by precomputing and periodically caching query results. \
close \
6. \
 \
You used Dataplex to create lakes and zones for your business data. However, some files are not being discovered. What could be the issue? \
The files are in Parquet format. \
You have scheduled discovery to run every hour. \
You have an exclude pattern that matches the files. \
close \
The files are in ORC format. \
Incorrect. ORC format is supported and the file should be discovered. \
close \
7. \
 \
Your data in BigQuery has some columns that are extremely sensitive. You need to enable only some users to see certain columns. What should you do? \
Use policy tags. \
close \
Use Identity and Access Management (IAM) permissions. \
Create a new table with the column's data. \
Create a new dataset with the column's data. \
Incorrect. IAM permissions do not provide the column-level access control granularity that this scenario requires. \
close \
8. \
 \
You have a complex set of data that comes from multiple sources. The analysts in your team need to analyze the data, visualize it, and publish reports to internal and external stakeholders. You need to make it easier for the analysts to work with the data by abstracting the multiple data sources. What tool do you recommend? \
Looker \
Connected Sheets \
close \
Looker Studio \
D3.js library \
Incorrect. Looker Studio (previously Data Studio) is a visualization tool that does not have the data abstraction capabilities of Looker modeling. \
check \
9. \
 \
Your business has collected industry-relevant data over many years. The processed data is useful for your partners and they are willing to pay for its usage. You need to ensure proper access control over the data. What should you do? \
Host the data on Cloud SQL. \
check \
Host the data on Analytics Hub. \
Export the data to zip files and share it through Cloud Storage. \
Export the data to persistent disks and share it through an FTP endpoint. \
Correct. Analytics Hub has the built-in options to connect publishers and subscribers with access control and to monetize data access. \
close \
10. \
 \
You have data in PostgreSQL that was designed to reduce redundancy. You are transferring this data to BigQuery for analytics. The source data is hierarchical and frequently queried together. You need to design a BigQuery schema that is performant. What should you do? \
close \
Copy the normalized data into partitions. \
Use nested and repeated fields. \
Retain the data in normalized form always. \
Copy the primary tables and use federated queries for secondary tables. \
Incorrect. The inefficiency of multiple, separate, normalized tables still exists even if you partition the table. \
