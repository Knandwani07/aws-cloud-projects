# 🔁 Automating Deployment from GitHub to Amazon S3

## 📌 Project Level: Intermediate
A practical AWS + DevOps project where you automate the deployment of static website files from a **GitHub repository** directly into an **S3 bucket** using IAM credentials.

This project teaches real-world automation by enabling continuous, code-driven updates to S3 without manually uploading files.

---

## 📝 Project Overview
This project walks through creating an S3 bucket, generating IAM credentials with the right permissions, configuring GitHub Secrets, and using GitHub’s upload interface to automatically sync code into S3.

Once set up, any file you upload, edit, or push inside GitHub can be deployed directly into S3, ideal for static websites, documentation, demos, or quick front-end deployments.

---

## 🎯 Objective
To automate the deployment of static files from GitHub into an S3 bucket using IAM credentials, enabling fast, repeatable, and code-driven updates without manual uploads.

---

## 🧰 AWS Services Used
- **Amazon S3** — Stores and hosts static files  
- **AWS IAM** — Generates programmatic access keys  
- **GitHub** — Stores source code and triggers uploads  
- **GitHub Secrets** — Securely stores AWS access credentials  

---

## 🧠 What This Project Teaches
- Creating and configuring an S3 bucket  
- Enabling **Bucket Versioning** for safe rollbacks  
- Creating an IAM user with S3-specific permissions  
- Generating **Access Key ID** and **Secret Access Key**  
- Storing credentials inside GitHub Secrets  
- Uploading files from GitHub → S3 using IAM authentication  
- Accessing hosted assets using the S3 object URL  
- Cleaning up S3 resources safely  

---

## 🚀 Project Steps (Simplified)
1️⃣ Create an S3 bucket with a unique name and enable Versioning.  
2️⃣ Create an IAM user with **AmazonS3FullAccess** or limited S3 permissions.  
3️⃣ Generate an Access Key & Secret Key for programmatic access.  
4️⃣ Store both keys in **GitHub Secrets**.  
5️⃣ Go to GitHub → Upload your project files into the repo.  
6️⃣ Use GitHub’s built-in “Upload to S3” integration (via Secrets).  
7️⃣ Refresh your S3 bucket to confirm the files were deployed.  
8️⃣ Open the object URL to verify successful hosting.  

Full detailed steps with screenshots are available in the project documentation.

---

## 🌟 Key Features
- Automated deployment flow using GitHub → S3  
- IAM-based authentication for secure uploads  
- Versioning enabled for rollback capability  
- No manual S3 uploads required  
- Ideal for static sites, landing pages, and documentation hosting  

---

## 🧹 Cleanup
To avoid unnecessary storage and avoid leaving unused access keys:

- Delete objects inside the S3 bucket  
- Delete the S3 bucket if no longer needed  
- Remove IAM access keys or delete the IAM user  
- Clear GitHub Secrets if automation is not required  

---

## 🏁 Outcome
This project demonstrates how to automate cloud deployments using GitHub and AWS.  
You learn the fundamentals of IAM-based programmatic access, automated file transfers, and S3-based hosting, essential DevOps and cloud engineering skills.

---

## 🎥 Project Demo Video
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode9-aws-activity-7298212281996247040-hzfr

---

## 📄 Full Project Documentation
👉 https://www.linkedin.com/posts/khushi-nandwani_automate-code-from-github-to-s3-project-documentation-activity-7298574665965334528-Io0J

---

## 🏷️ Tags
`AWS S3` `DevOps Automation` `GitHub Integration` `S3 Deployment`  
`Static Hosting` `IAM Credentials` `Cloud Automation` `Intermediate AWS Project`
