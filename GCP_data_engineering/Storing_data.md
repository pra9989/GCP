Preparing for your Professional Data Engineer Journey \
Storing cymbal retails data \
Professional Data Engineer in storing data in Google Cloud for Cymbal Retail, including data architecture, database selection, and data lifecycle management. \
As a Professional Data Engineer, you role is deeply intertwined with how Cymbal Retail uses data.\
Cymbal Retail ingests, stores, processes, and analyzes many types of data, including documents, images, text, and video. \
Choosing appropriate storage solutions on google cloud \
Ensuring the data lifecycle compiles with data privacy rules \
Your data engineering team must ensure that data follows a well-defined lifecycle. \
Each region's laws define a strict timeline for the retention and deletion of customer data.\
You need to set controls in place so that individuals do not accidentally breach rules.\
It is also your responsibility as a Professional Data Engineer to continue to maintain Cymbal Retail’s data for effective use.\
Evolving data architecture as business needs change \
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
Questions:
Your score: 30% Passing score: 80% \
Unfortunately, you need at least a 80% to pass this assessment. Not to worry though, review your answers and try again. \
check \
1. \
 \
You have data that is ingested daily and frequently analyzed in the first month. Thereafter, the data is retained only for audits, which happen occasionally every few years. You need to configure cost-effective storage. What should you do? \
Create a bucket on Cloud Storage with object versioning configured. \
Create a bucket on Cloud Storage with Autoclass configured. \
Configure a data retention policy on Cloud Storage. \
check \
Configure a lifecycle policy on Cloud Storage. \
Correct. A lifecycle policy can be configured to automatically move the objects between different storage classes on schedules that you determine. \
close \
2. \
 \
You need to store data long term and use it to create quarterly reports. What storage class should you choose? \
Archive \
Standard \
Coldline \
close \
Nearline \
Incorrect. Nearline storage class is the recommended option when the data is accessed less frequently, such as once a month. \
close \
3. \
 \
You have large amounts of data stored on Cloud Storage and BigQuery. Some of it is processed, but some is yet unprocessed. You have a data mesh created in Dataplex. You need to make it convenient for internal users of the data to discover and use the data. What should you do? \
Create a raw zone for the unprocessed data and a curated zone for the processed data. \
Create a lake for Cloud Storage data and a zone for BigQuery data. \
Create a lake for BigQuery data and a zone for Cloud Storage data. \
close \
Create a lake for unprocessed data and assets for processed data. \
Incorrect. A zone is where we make a distinction between processed and unprocessed data. \
close \
4. \
 \
You have several large tables in your transaction databases. You need to move all the data to BigQuery for the business analysts to explore and analyze the data. How should you design the schema in BigQuery? \
Retain the data on BigQuery with the same schema as the source. \
Combine all the transactional database tables into a single table using outer joins. \
close \
Redesign the schema to normalize the data by removing all redundancies. \
Redesign the schema to denormalize the data with nested and repeated data. \
Incorrect. Normalizing the data is not the recommended approach for BigQuery. \
close \
5. \
 \
You have data stored in a Cloud Storage bucket. You are using both Identity and Access Management (IAM) and Access Control Lists (ACLs) to configure access control. Which statement describes a user's access to objects in the bucket? \
The user has no access if either IAM or ACLs deny a permission. \
The user has no access if IAM denies the permission. \
close \
The user only has access if both IAM and ACLs grant a permission. \
The user has access if either IAM or ACLs grant a permission. \
Incorrect. Permissions need not be congruently set in both; either can give access. \
check \
6. \
 \
A manager at Cymbal Retail expresses concern about unauthorized access to objects in your Cloud Storage bucket. You need to evaluate all access on all objects in the bucket. What should you do? \
Route the Admin Activity logs to a BigQuery sink and analyze the logs with SQL queries. \
Change the permissions on the bucket to only trusted employees. \
Review the Admin Activity audit logs. \
check \
Enable and then review the Data Access audit logs. \
Correct. Data Access audit logs have to be specifically enabled first, because they could generate a lot of logs for all reads and writes. \
check \
7. \
 \
Cymbal Retail has accumulated a large amount of data. Analysts and leadership are finding it difficult to understand the meaning of the data, such as BigQuery columns. Users of the data don't know who owns what. You need to improve the searchability of the data. What should you do? \
Export the data to Cloud Storage with descriptive file names. \
check \
Create tags for data entries in Cloud Catalog. \
Rename BigQuery columns with more descriptive names. \
Add a description column corresponding to each data column. \
Correct. Tags enable attaching metadata to data assets and entities. This can improve searchability of the data. \
close \
8. \
 \
Your analysts repeatedly run the same complex queries that combine and filter through a lot of data on BigQuery. The data changes frequently. You need to reduce the effort for the analysts. What should you do? \
close \
Export the frequently queried data into Cloud SQL. \
Create a dataset with the data that is frequently queried. \
Export the frequently queried data into a new table. \
Create a view of the frequently queried data. \
Incorrect. It requires more effort and cost to duplicate the data in another database. \
close \
9. \
 \
You are ingesting data that is spread out over a wide range of dates into BigQuery at a fast rate. You need to partition the table to make queries performant. What should you do? \
Create an integer-range partitioned table. \
Create an ingestion-time partitioned table with daily partitioning type. \
close \
Create an ingestion-time partitioned table with yearly partitioning type. \
Create a time-unit column-partitioned table with yearly partitioning type. \
Incorrect. A yearly partition type has too much data per partition, which makes queries inefficient. \
close \
10. \
 \
You need to choose a data storage solution to support a transactional system. Your customers are primarily based in one region. You want to reduce your administration tasks and focus engineering effort on building your business application. What should you do? \
Create a Cloud Storage bucket with a regional bucket. \
close \
Use Spanner. \
Install a database of your choice on a Compute Engine VM. \
Use Cloud SQL. \
Incorrect. Spanner is more suitable for a global, transactional database requirement. \


