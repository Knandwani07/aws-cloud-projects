# 🔍 Analyzing CloudFront Logs with Amazon Athena  
## 📌 Project Level: Intermediate  

A hands-on AWS data analytics project where you use **Amazon Athena** to query and analyze **CloudFront logs** stored in Amazon S3.  
This project demonstrates how serverless, SQL-based analytics can be performed without provisioning any infrastructure.

You build a workflow that collects CloudFront logs, catalogs them using AWS Glue, and queries them using Athena to extract insights such as request patterns, status codes, IP distributions, and user behavior.

---

## 📝 Project Overview  
This project walks through configuring **CloudFront logging**, storing logs in **Amazon S3**, creating a **Glue Crawler** to maintain table schema, and using **Amazon Athena** to run SQL queries against the dataset.

You learn how to explore CloudFront access logs to analyze traffic trends, performance metrics, and content delivery behavior using simple SQL queries all in a fully serverless environment.

---

## 🎯 Objective  
To enable log-based analytics using CloudFront, S3, Glue Data Catalog, and Athena by creating a serverless querying workflow to visualize and understand CDN traffic patterns.

---

## 🧰 AWS Services Used  
- **Amazon S3** — Storage location for CloudFront logs  
- **Amazon CloudFront** — CDN generating access logs  
- **AWS Glue Crawler** — Automated schema detection & table creation  
- **AWS Glue Data Catalog** — Central metadata store  
- **Amazon Athena** — Query engine for serverless analytics  

---

## 🧠 What This Project Teaches  
- Enabling logging for a CloudFront Distribution  
- Storing logs in S3 in the correct folder structure  
- Using a Glue Crawler to detect and create table schema  
- Running SQL queries on CloudFront logs with Athena  
- Understanding log fields such as:
  - Edge locations  
  - HTTP status codes  
  - Cache behaviors  
  - Request URLs  
  - User IPs  
- Performing exploratory data analysis directly from S3  
- Using serverless analytics without provisioning compute  

---

## 🚀 Project Steps (Simplified)

1. Enable **CloudFront Standard Logs** and select an S3 bucket as the target.  
2. Wait for log files to populate inside the S3 bucket.  
3. Open **AWS Glue** → create a Crawler to index the log folder.  
4. Run the Crawler to generate a table inside the Glue Data Catalog.  
5. Open **Amazon Athena** and select the database created by Glue.  
6. Start querying the CloudFront logs using SQL.  
   Examples:  
   - Count requests  
   - Top IP addresses  
   - Status code distribution  
   - Cache hit/miss analysis  
7. Save and export query results if needed.  

Full detailed steps with screenshots are available in the project documentation.

---

## 🌟 Key Features  
- End-to-end log analytics workflow  
- Automatically derived schema using Glue  
- Fully serverless querying with Athena  
- Zero infrastructure maintenance  
- Ability to run SQL queries directly from S3  
- Practical insights into CloudFront traffic behaviors  

---

## 🧹 Cleanup  
To avoid unnecessary charges:

- Disable CloudFront logging  
- Delete logs from S3  
- Delete Glue Crawler and its metadata  
- Drop the Athena table or database (optional)  

---

## 🏁 Outcome  
By completing this project, you gain hands-on experience in building a **serverless log analytics pipeline** using CloudFront, S3, Glue, and Athena.  
You learn how to process and query real log data without managing servers or databases—an essential skill in cloud analytics and observability.

---

## 🎥 Project Demo Video  
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode16-aws-activity-7329015269765349376-HJqQ  

---

## 📄 Full Project Documentation  
👉 https://www.linkedin.com/posts/khushi-nandwani_athena-documentation-activity-7329443047199432704-9piO  

---

## 🏷️ Tags  
`Amazon Athena` `AWS Glue` `CloudFront Logs` `Serverless Analytics`  
`Amazon S3` `SQL Queries` `Log Analysis` `Intermediate AWS Project`

