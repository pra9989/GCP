quesition and answers \
Your score: 40% Passing score: 80% \
Unfortunately, you need at least a 80% to pass this assessment. Not to worry though, review your answers and try again. \
close \
1. \
 \
Business analysts in your team need to run analysis on data that was loaded into BigQuery. You need to follow recommended practices and grant permissions. What role should you grant the business analysts? \
close \
storage.objectViewer and bigquery.user \
bigquery.dataOwner \
bigquery.resourceViewer and bigquery.dataViewer \
bigquery.user and bigquery.dataViewer \
Incorrect. The storage.objectViewer role is useful when running federated queries with Cloud Storage, but not for this use case. The business analysts will also require permissions in the bigquery.dataViewer role. \
close \
2. \
 \
You are using Dataproc to process a large number of CSV files. The storage option you choose needs to be flexible to serve many worker nodes in multiple clusters. These worker nodes will read the data and also write to it for intermediate storage between processing jobs. What is the recommended storage option on Google Cloud? \
Local SSD \
Cloud Storage \
Cloud SQL \
close \
Zonal persistent disks \
Incorrect. Zonal Persistent Disks are not the recommended option for Dataproc storage. \
close \
3. \
 \
You are running a user-supplied DoFn method signature pipeline in Dataflow. The function has been defined by you. The code is running slow and you want to further examine the pipeline code to get better visibility of why. What should you do? \
Use Cloud Monitoring \
Use Cloud Logging \
close \
Use Cloud Audit Logs \
Use Cloud Profiler \
Incorrect. Cloud Audit Logs capture administrative events. They do not provide sufficient data to identify Dataflow resource usage. \
close \
4. \
 \
Cymbal Retail has acquired another company in Europe. Data access permissions and policies in this new region differ from those in Cymbal Retail’s headquarters, which is in North America. You need to define a consistent set of policies for projects in each region that follow recommended practices. What should you do? \
Implement policies at the resource level that comply with regional laws. \
Create top level folders for each region, and assign policies at the folder level. \
close \
Create a new organization for all projects in Europe and assign policies in each organization that comply with regional laws. \
Implement a flat hierarchy, and assign policies to each project according to its region. \
Incorrect. Creating a new organization to apply separate policies or to work with a different region is not a recommended practice. This requirement can be managed within the same organization by using folders. \
close \
5. \
 \
Laws in the region where you operate require that files related to all orders made each day are stored immutably for 365 days. The solution that you recommend has to be cost-effective. What should you do? \
Store the data in a Cloud Storage bucket, and enable object versioning and delete any version older than 365 days. \
Store the data in a Cloud Storage bucket, and specify a retention period. \
Store the data in a Cloud Storage bucket, enable object versioning, and delete any version greater than 365. \
close \
Store the data in a Cloud Storage bucket, and set a lifecycle policy to delete the file after 365 days. \
Incorrect. This option automates the deletion of the file after 365 days, but it does not restrict the deletion of the file before that. \
check \
6. \
 \
Cymbal Retail is migrating its private data centers to Google Cloud. Over many years, hundreds of terabytes of data were accumulated. You currently have a 100 Mbps line and you need to transfer this data reliably before commencing operations on Google Cloud in 45 days. What should you do? \
check \
Order a transfer appliance, export the data to it, and ship it to Google. \
Store the data in an HTTPS endpoint, and configure Storage Transfer Service to copy the data to Cloud Storage. \
Upload the data to Cloud Storage by using gcloud storage. \
Zip and upload the data to Cloud Storage buckets by using the Google Cloud console. \
Correct. For large amounts of data that need to be transferred within a month, a transfer appliance is the right choice. \
close \
7. \
 \
You are managing the data for Cymbal Retail, which consists of multiple teams including retail, sales, marketing, and legal. These teams are consuming data from multiple producers including point of sales systems, industry data, orders, and more. Currently, teams that consume data have to repeatedly ask the teams that produce it to verify the most up-to-date data and to clarify other questions about the data, such as source and ownership. This process is unreliable and time-consuming and often leads to repeated escalations. You need to implement a centralized solution that gains a unified view of the organization's data and improves searchability. What should you do? \
Implement a data mesh with Dataplex and have producers tag data when created. \
Implement a data lake with Cloud Storage, and create buckets for each team such as retail, sales, marketing. \
Implement Looker dashboards that provide views of the data that meet each teams’ requirements. \
close \
Implement a data warehouse by using BigQuery, and create datasets for each team such as retail, sales, marketing. \
Incorrect. BigQuery can separate the data in datasets, but it is not a centralized data discovery solution that can hold different types of data. \
check \
8. \
 \
Cymbal Retail has a team of business analysts who need to fix and enhance a set of large input data files. For example, duplicates need to be removed, erroneous rows should be deleted, and missing data should be added. These steps need to be performed on all the present set of files and any files received in the future in a repeatable, automated process. The business analysts are not adept at programming. What should they do? \
Load the data into Google Sheets, explore the data, and fix the data as needed. \
Create a Dataflow pipeline with the data fixes you need. \
check \
Load the data into Dataprep, explore the data, and edit the transformations as needed. \
Create a Dataproc job to perform the data fixes you need. \
Correct. Dataprep lets you load large amounts of data and visually fix it, which would be very convenient for those who are unfamiliar with programming. The data wrangling steps can be captured as a series of transformations that can be reapplied later to future data. \
check \
9. \
 \
Your data and applications reside in multiple geographies on Google Cloud. Some regional laws require you to hold your own keys outside of the cloud provider environment, whereas other laws are less restrictive and allow storing keys with the same provider who stores the data. The management of these keys has increased in complexity, and you need a solution that can centrally manage all your keys. What should you do? \
check \
Store your keys on a supported external key management partner, and use Cloud External Key Manager (Cloud EKM) to get keys when required. \
Store your keys in Cloud Hardware Security Module (Cloud HSM), and retrieve keys from it when required. \
Enable confidential computing for all your virtual machines. \
Store keys in Cloud Key Management Service (Cloud KMS), and reduce the number of days for automatic key rotation. \
Correct. With Cloud EKM, you manage access to your externally managed keys that reside outside of Google Cloud. Because you need a single solution that also has to store keys externally, this would be the appropriate option. \
check \
10. \
 \
You are migrating on-premises data to a data warehouse on Google Cloud. This data will be made available to business analysts. Local regulations require that customer information including credit card numbers, phone numbers, and email IDs be captured, but not used in analysis. You need to use a reliable, recommended solution to redact the sensitive data. What should you do? \
check \
Use the Cloud Data Loss Prevention API (DLP API) to identify and redact data that matches infoTypes like credit card numbers, phone numbers, and email IDs. \
Create a regular expression to identify and delete patterns that resemble credit card numbers, phone numbers, and email IDs. \
Delete all columns with a title similar to "credit card," "phone," and "email." \
Use the Cloud Data Loss Prevention API (DLP API) to perform date shifting of any entries with credit card numbers, phone numbers, and email IDs. \
Correct. The Cloud Data Loss Prevention API, part of Sensitive Data Protection, helps you discover, classify, and protect your most sensitive data. There are predefined infoTypes that you can employ to identify and redact specific data types. \

Your score: 50% Passing score: 50% \
Congratulations! You passed this assessment. \
close \
1. \
 \
Your company is very serious about data protection and hence decides to implement the Principle of Least Privilege. What should you do to comply with this policy? \
close \
Ensure that the access permissions are given strictly based on the person’s title and job role. \
Ensure that the users are verified every time they request access, even if they were authenticated earlier. \
Give just enough permissions to get the task done. \
When a task is assigned, ensure that it gets assigned to a person with the minimum privileges. \
Incorrect. \
check \
2. \
 \
A company collects lots of consumer data from online marketing campaigns. Company plans to use Google Cloud to store this collected data. The top management is worried about exposing personally identifiable information (PII) that may be present in this data. What should you do to reduce the risk of exposing PII data? \
Store all data in BigQuery and turn on column level access to protect sensitive data. \
Ensure that all PII data is removed from the collected data before storing it on Google Cloud. \
check \
Use the Cloud Data Loss Prevention API (DLP API) to inspect and redact PII data. \
Ensure that all stored data is monitored by Security Command Center. \
Correct. \
