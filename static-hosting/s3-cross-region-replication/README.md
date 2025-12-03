
# 🌍 Amazon S3 Cross-Region Replication (CRR)

## 📌 Project Level: Intermediate
A practical AWS project where you configure **Cross-Region Replication (CRR)** between two S3 buckets.  
This ensures that objects uploaded in one region are automatically copied to another region for backup, disaster recovery, or compliance purposes.

---

## 📝 Project Overview
This project walks through creating a source bucket and a destination bucket in two different AWS regions and enabling CRR between them.  
You configure Versioning, create the required IAM role, define replication rules, and validate the replication by uploading test files.

CRR is widely used for business continuity, redundancy, and global resilience making it a key real-world cloud engineering skill.

---

## 🎯 Objective
To replicate objects automatically from a source S3 bucket to a destination S3 bucket in a different AWS region using S3 Cross-Region Replication.

---

## 🧰 AWS Services Used
- **Amazon S3** — Primary storage service for buckets  
- **S3 Versioning** — Required for replication  
- **IAM Roles** — Permissions for S3 to perform replication  
- **S3 Replication Rules** — Define what gets copied and where  
- **Cross-Region Architecture** — Ensures resilience across two AWS regions  

---

## 🧠 What This Project Teaches
- Creating S3 buckets in different regions  
- Enabling **Versioning** on both source and destination buckets  
- Understanding IAM roles created automatically by S3  
- Creating and configuring replication rules  
- Testing CRR by uploading objects to the source bucket  
- Validating successful replication in the destination bucket  
- Cleaning up replicated objects and buckets responsibly  

---

## 🚀 Project Steps (Simplified)
1️⃣ Create a **source S3 bucket** in Region A.  
2️⃣ Create a **destination S3 bucket** in Region B.  
3️⃣ Enable **Versioning** on both buckets.  
4️⃣ Open the source bucket → Select **Replication**.  
5️⃣ Create a replication rule and choose the destination bucket.  
6️⃣ Allow S3 to create the required **IAM role** automatically.  
7️⃣ Save the rule and upload test files to the source bucket.  
8️⃣ Verify that files appear in the destination bucket automatically.

Full detailed steps with screenshots are available in the project documentation.

---

## 🌟 Key Features
- Fully automated cross-region redundancy  
- Strong disaster recovery and backup mechanism  
- Version-controlled replication for added safety  
- Real-world multi-region AWS architecture  
- IAM role–based secure replication workflow  

---

## 🧹 Cleanup
To avoid unnecessary storage charges:

- Delete replicated objects from both buckets  
- Turn off replication rules  
- Delete both S3 buckets if no longer needed  
- Remove the IAM role if it is not needed for future replication tasks  

---

## 🏁 Outcome
You gain practical experience configuring cross-region replication to ensure high availability, resilience, and disaster recovery.  
This project builds your understanding of **multi-region AWS architectures**, **backup strategies**, and **automated S3 operations** — essential for cloud and DevOps roles.

---

## 🎥 Project Demo Video
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode2-aws-activity-7287706805483233280-AE0C

---

## 📄 Full Project Documentation
👉 https://www.linkedin.com/posts/khushi-nandwani_s3-crr-documentation-activity-7288065467334713344-m9oB

---

## 🏷️ Tags
`S3 Replication` `Cross Region Replication` `Multi-Region Architecture`  
`Disaster Recovery` `Versioning` `Intermediate AWS Project` `S3 Automation`
