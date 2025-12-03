# 🔄 Serverless Data Analytics with AWS Data Exchange, S3 & Athena  
## 📌 Project Level: Intermediate  

A serverless AWS data analytics project where you subscribe to a public dataset using **AWS Data Exchange**, store it in **Amazon S3**, catalog it with **AWS Glue**, and analyze it using **Amazon Athena**.  
This project showcases a real-world workflow for acquiring third-party datasets, automating metadata creation, and performing SQL-based analytics all without provisioning servers.

---

## 📝 Project Overview  
This project walks through subscribing to a dataset from **AWS Data Exchange**, exporting the data to an S3 bucket, setting up a Glue Crawler to automatically detect schema, and writing SQL queries in Athena to generate insights.

You explore how Data Exchange integrates seamlessly with S3 and how Athena can query structured and semi-structured files instantly.  
This end-to-end workflow demonstrates modern, serverless data ingestion and analytics practices.

---

## 🎯 Objective  
To acquire, store, catalog, and analyze a third-party dataset from AWS Data Exchange using fully managed AWS services: S3, Glue Data Catalog, and Athena.

---

## 🧰 AWS Services Used  
- **AWS Data Exchange** — Browse and subscribe to third-party datasets  
- **Amazon S3** — Storage for exported dataset files  
- **AWS Glue Crawler** — Automatic schema detection & table creation  
- **AWS Glue Data Catalog** — Metadata storage  
- **Amazon Athena** — SQL querying of analytics datasets  

---

## 🧠 What This Project Teaches  
- How to browse and subscribe to datasets in AWS Data Exchange  
- Exporting licensed datasets directly to S3 buckets  
- Using Glue Crawlers to detect table schema  
- Understanding partitioning and metadata creation  
- Executing SQL queries in Athena for analysis  
- Extracting valuable insights from structured datasets  
- End-to-end, serverless data ingestion → cataloging → querying workflow  

---

## 🚀 Project Steps (Simplified)

1. Open **AWS Data Exchange** and subscribe to a public dataset.  
2. Export the dataset to Amazon S3 (choose the correct bucket and folder path).  
3. Open **AWS Glue**, create and run a Crawler for the exported dataset.  
4. Verify that a new table appears inside the Glue Data Catalog.  
5. Open **Amazon Athena**, select the database created by the Crawler.  
6. Write SQL queries to analyze the dataset:
   - Counting rows  
   - Filtering values  
   - Aggregating numeric metrics  
   - Extracting patterns from columns  
7. Save or download the query results if needed.  

Full detailed steps with screenshots are available in the project documentation.

---

## 🌟 Key Features  
- Practical integration between AWS Data Exchange and S3  
- Automatic metadata detection using Glue Crawlers  
- Serverless SQL analytics with Athena  
- No infrastructure provisioning or maintenance  
- Real-world data ingestion and exploration workflow  

---

## 🧹 Cleanup  
To avoid unnecessary charges:

- Unsubscribe from the Data Exchange dataset (if not needed)  
- Delete dataset exports from S3  
- Remove Glue Crawler and associated metadata  
- Drop Athena tables or the database (optional)  

---

## 🏁 Outcome  
By completing this project, you learn how to acquire external datasets and build a fully serverless analytics workflow using AWS Data Exchange, S3, Glue, and Athena.  
This project strengthens your knowledge of AWS analytics pipelines and real-world data engineering practices.

---

## 🎥 Project Demo Video  
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode17-aws-activity-7334088725737476097-TJ84  

---

## 📄 Full Project Documentation  
👉 https://www.linkedin.com/posts/khushi-nandwani_serverless-data-analytics-project-documentation-activity-7334451069625815040-_v78  

---

## 🏷️ Tags  
`AWS Data Exchange` `Amazon S3` `AWS Glue` `Athena`  
`Data Engineering` `Serverless Analytics` `Intermediate AWS Project`


