# 🗄️ Scalable MariaDB Architecture using RDS + EC2  
## 📌 Project Level: Intermediate  

A hands-on AWS project where you deploy a **production-style MariaDB database** using Amazon RDS and connect it to a Linux EC2 instance.  
This project mirrors real-world backend architectures with managed databases, secure networking, and SQL connectivity.

---

## 📝 Project Overview  
This project walks through launching an **Amazon RDS MariaDB instance**, configuring security groups, setting up an **EC2 Linux server**, installing the MySQL client, and connecting securely to the database.

It highlights how compute and database layers remain isolated yet connected an AWS best practice for scalable architectures.

---

## 🎯 Objective  
To deploy a secure MariaDB database using **Amazon RDS** and connect to it from an **EC2 instance**, performing SQL operations and validating full end-to-end communication.

---

## 🧰 AWS Services Used  
- **Amazon RDS (MariaDB)** — Managed database service  
- **Amazon EC2** — Application server used to connect to RDS  
- **Security Groups** — Controlled access on port 3306  
- **VPC & Subnets** — Database networking infrastructure  
- **Automated Backups** — RDS-managed snapshots  

---

## 🧠 What This Project Teaches  
- Launching and configuring RDS MariaDB  
- Creating EC2 instances and installing the MySQL client  
- Configuring secure SG-to-SG communication  
- Connecting EC2 to RDS using RDS endpoint  
- Running SQL queries (creating DB, tables, inserting data)  
- Cleaning up RDS + EC2 resources responsibly  

---

## 🚀 Project Steps (Simplified)

1️⃣ Launch an **Amazon RDS MariaDB** instance with free-tier settings.  
2️⃣ Configure master username, password, subnet groups, and SG rules.  
3️⃣ Allow inbound **port 3306** from the EC2 security group.  
4️⃣ Launch an **EC2 Linux instance** in the same VPC.  
5️⃣ Install MySQL client tools on the EC2 server.  
6️⃣ Connect to RDS using the endpoint and credentials.  
7️⃣ Run SQL commands to create a database, tables, and insert sample data.  
8️⃣ Validate successful EC2 ↔ RDS connectivity.

Full detailed steps with screenshots are available in the documentation.

---

## 🌟 Key Features  
- Secure RDS connectivity  
- Managed backups and maintenance  
- Real compute ↔ database separation  
- SQL operations from EC2 terminal  
- Cloud-ready backend architecture  

---

## 🧹 Cleanup  
To prevent unwanted charges:

- Delete the **RDS instance**  
- Terminate the **EC2 instance**  
- Remove security groups  
- Delete any custom subnet groups  

---

## 🏁 Outcome  
You gain hands-on experience deploying a **scalable, secure, cloud-native MariaDB backend**.  
This project strengthens your understanding of AWS networking, database management, and production-like architectural design.

---

## 🎥 Project Demo Video  
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode12-rds-activity-7316348886057447424-m31U  

---

## 📄 Full Project Documentation  
👉 https://www.linkedin.com/posts/khushi-nandwani_rds-project-documentation-activity-7316709505730306048-CPXa  

---

## 🏷️ Tags  
`AWS RDS` `MariaDB` `EC2` `Cloud Databases` `SQL` `Backend Architecture` `Intermediate AWS Project`
