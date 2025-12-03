# 🌐 High Availability VPC Architecture on AWS

## 📌 Project Level: Intermediate
A hands-on AWS networking project where you design and build a **High Availability VPC Architecture** consisting of public and private subnets across multiple Availability Zones, internet access via an Internet Gateway, NAT Gateway communication for private subnets, and proper route table configurations.

This project provides practical experience in designing fault-tolerant, production-ready AWS network foundations.

---

## 📝 Project Overview
This project walks through creating a fully functional **Virtual Private Cloud (VPC)** with high availability in mind.  
You build two public subnets and two private subnets across two Availability Zones, attach an Internet Gateway, configure NAT Gateway access, and set up the necessary route tables to ensure correct traffic flow.

This architecture allows public-facing resources (like web servers) and private internal resources (like databases or backend services) to operate securely and reliably in a multi-AZ AWS network.

---

## 🎯 Objective
To design and deploy a **multi-AZ, highly available VPC architecture** with segregated public/private subnets and proper routing that ensures secure and fault-tolerant communication between AWS resources.

---

## 🧰 AWS Services Used
- **Amazon VPC** — Core networking environment  
- **Subnets (Public & Private)** — Logical network segmentation  
- **Internet Gateway (IGW)** — Internet access for public subnets  
- **NAT Gateway** — Outbound internet access for private subnets  
- **Route Tables** — Control network traffic routing  
- **Elastic IP** — Required for NAT Gateway  
- **Availability Zones** — Ensures high availability  

---

## 🧠 What This Project Teaches
- Designing a VPC with a standard production-ready layout  
- Creating and configuring public and private subnets  
- Attaching and configuring an Internet Gateway  
- Creating a NAT Gateway for private subnet internet access  
- Assigning route tables and associating them with subnets  
- Understanding CIDR allocation best practices  
- Ensuring high availability through multi-AZ design  
- Verifying connectivity of public and private subnet resources  

---

## 🚀 Project Steps (Simplified)
1️⃣ Create a **VPC** with an appropriate CIDR range.  
2️⃣ Create two **public subnets** in different Availability Zones.  
3️⃣ Create two **private subnets** in different Availability Zones.  
4️⃣ Attach an **Internet Gateway** to enable public internet access.  
5️⃣ Create a **NAT Gateway** inside a public subnet using an Elastic IP.  
6️⃣ Configure **route tables**:  
                                - Public route table → IGW  
                                - Private route table → NAT Gateway  
7️⃣ Associate each subnet with its correct route table.  
8️⃣ Optionally launch EC2 instances in public/private subnets to validate routing.  
9️⃣ Verify high availability across two AZs.

Full detailed steps with screenshots are available in the project documentation.

---

## 🌟 Key Features
- Fully designed **multi-AZ network architecture**  
- Realistic VPC structure used in production deployments  
- Secure separation of public and private workloads  
- Internet and NAT routing configured properly  
- Foundation for scalable architectures like ALB, ASG, EKS, RDS, etc.  
- Clear understanding of AWS networking fundamentals  

---

## 🧹 Cleanup
To prevent unnecessary charges:
- Delete NAT Gateway (this incurs cost)  
- Release associated Elastic IP  
- Delete Internet Gateway  
- Remove subnets  
- Delete the VPC  

---

## 🏁 Outcome
By completing this project, you gain strong knowledge of AWS networking foundations—VPC design, public/private subnet configurations, multi-AZ architecture, IGW/NAT routing, and secure segmentation.

This is a critical skill for building production-grade cloud architectures.

---

## 🎥 Project Demo Video
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode10-aws-activity-7302588644660314112-fFTD

---

## 📄 Full Project Documentation
👉 https://www.linkedin.com/posts/khushi-nandwani_vpc-activity-7302932926873174017-THJX

---

## 🏷️ Tags
`AWS VPC` `High Availability` `Public & Private Subnets` `Internet Gateway`  
`NAT Gateway` `Route Tables` `AWS Networking` `Intermediate AWS Project`

