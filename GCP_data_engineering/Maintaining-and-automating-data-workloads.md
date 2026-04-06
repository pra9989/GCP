MODULE 5 \
Maintaining-and-automating-data-workloads \
Maintaining-and-automating-data-workloads at cymbal Retail \
Diagnostic questions \
Review and study planning \
Maintaining and automating data workloads at cymbal retail \
Ensuring cost effectiveness and correctness \
> automation and observability \
> Monitoring and managing workloads\
> balancing compute capacity, error handling and costs \
BALANCING USER EXPERIENCE AND COST EFFICIENCY \
Cymbal retails needs to provide excellent end user experience \
> Fast web pages and purchases \
> High availability \
LOOKING FOR WAYS TO AUTOMATE AND SCALE \
> how can you optimize through automation \
> how can you boost efficency ? \
> what notifications and thresholds can you appropriately set to reduce manintenance time and effort \
PROVIDING INDEPENDENCE AND FLEXIBILITY TO MEET USAGE DEMANDS \
> Sales and marketing need to run campagins which temporarily spike demand \
> You need to find a solution to automatically scale resources as needed \
BALANCING USER EXPERIENCE AND COST EFFICIENCY \
> fast web pages and purchases \
> HIgh availability \
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>.  99999  0000 \1. \
 \
You run a Cloud SQL instance for a business that requires that the database is accessible for transactions. You need to ensure minimal downtime for database transactions. What should you do? \
Configure backups. \
Configure replication. \
Configure high availability. \
Configure backups and increase the number of backups. \
2. \
 \
You have a team of data analysts that run queries interactively on BigQuery during work hours. You also have thousands of report generation queries that run simultaneously. You often see an error: Exceeded rate limits: too many concurrent queries for this project_and_region. How would you resolve this issue? \
Run all queries in interactive mode. \
Create a yearly reservation of BigQuery slots. \
Run the report generation queries in batch mode. \
Create a view to run the queries. \
3. \
 \
You need to design a Dataproc cluster to run multiple small jobs. Many jobs (but not all) are of high priority. What should you do? \
Reuse the same cluster and run each job in sequence. \
Reuse the same cluster to run all jobs in parallel. \
Use ephemeral clusters. \
Use cluster autoscaling. \
4. \
 \
Multiple analysts need to prepare reports on Monday mornings due to which there is heavy utilization of BigQuery. You want to take a cost-effective approach to managing this demand. What should you do? \
Use BigQuery Enterprise Plus edition with a three-year commitment. \
Use on-demand pricing. \
Use Flex Slots. \
Use BigQuery Enterprise edition with a one-year commitment. \
5. \
 \
You are running a Dataflow pipeline in production. The input data for this pipeline is occasionally inconsistent. Separately from processing the valid data, you want to efficiently capture the erroneous input data for analysis. What should you do? \
Check for the erroneous data in the logs. \
Create a side output for the erroneous data. \
Re-read the input data and create separate outputs for valid and erroneous data. \
Read the data once, and split it into two pipelines, one to output valid data and another to output erroneous data. \
6. \
 \
When running Dataflow jobs, you see this error in the logs: "A hot key HOT_KEY_NAME was detected in…". You need to resolve this issue and make the workload performant. What should you do? \
Disable Dataflow shuffle. \
Increase the data with the hot key. \
Ensure that your data is evenly distributed. \
Add more compute instances for processing. \
7. \
 \
A colleague at Cymbal Retail asks you about the configuration of Dataproc autoscaling for a project. What would be the Google-recommended situation when you should enable autoscaling? \
When you want to down-scale idle clusters to minimum size. \
When there are different size workloads on the cluster. \
When you want to scale on-cluster Hadoop Distributed File System (HDFS). \
When you want to scale out single-job clusters. \
8. \
 \
You have a Dataflow pipeline in production. For certain data, the system seems to be stuck longer than usual. This is causing delays in the pipeline execution. You want to reliably and proactively track and resolve such issues. What should you do? \
Review the Cloud Monitoring dashboard regularly. \
Review the Dataflow logs regularly. \
Set up alerts with Cloud Run functions code that reviews the audit logs regularly. \
Set up alerts on Cloud Monitoring based on system lag. \
9. \
 \
You need to create repeatable data processing tasks by using Cloud Composer. You need to follow best practices and recommended approaches. What should you do? \
Combine multiple functionalities in a single task execution. \
Update data with INSERT statements during the task run. \
Write each task to be responsible for one operation. \
Use current time with the now() function for computation. \
10. \
 \
Cymbal Retail processes streaming data on Dataflow with Pub/Sub as a source. You need to plan for disaster recovery and protect against zonal failures. What should you do? \
Take Dataflow snapshots periodically. \
Create Dataflow jobs from templates. \
Enable vertical autoscaling. \
Enable Dataflow shuffle. \

<img width="1765" height="875" alt="image" src="https://github.com/user-attachments/assets/c1d2dc2e-9d77-4e7f-b027-2ec79ac6c03b" />
<img width="1565" height="886" alt="image" src="https://github.com/user-attachments/assets/e6aa10fc-7fcc-4dd4-8d4f-cbcf06f4476a" />
