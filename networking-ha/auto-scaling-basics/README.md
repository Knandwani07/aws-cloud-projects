# 📈 Auto Scaling Basics (AWS Auto Scaling Group)

## 📌 Project Level: Beginner–Intermediate
A hands-on AWS project where you configure an **Auto Scaling Group (ASG)** using a Launch Template to automatically scale EC2 instances based on demand.  
This project builds fundamental understanding of scalable cloud architecture and automated instance management.

---

## 📝 Project Overview
This project walks through creating a **Launch Template**, configuring an **Auto Scaling Group**, selecting Availability Zones, setting desired, minimum, and maximum capacity, and verifying that new EC2 instances launch automatically.

You also learn how to review activity logs inside the ASG dashboard and properly clean up resources after completion.  

---

## 🎯 Objective
To configure an Auto Scaling Group that automatically adjusts EC2 instance capacity based on defined scaling parameters, ensuring cost efficiency and high availability.  

---

## 🧰 AWS Services Used
- **Amazon EC2** — For launching cloud instances  
- **Launch Templates** — To standardize AMI, instance type, and configuration  
- **Auto Scaling Groups (ASG)** — For automated scaling of instances  
- **VPC & Subnets** — For selecting Availability Zones  
- **Activity Dashboard** — For monitoring ASG behavior  

---

## 🧠 What This Project Teaches
- Creating and configuring **Launch Templates**  
- Selecting **Availability Zones and Subnets** for ASG deployment  
- Setting **Desired, Minimum, and Maximum** capacities  
- Understanding ASG behavior through **Activity logs**  
- Monitoring EC2 instances launched automatically    
- Cleaning up ASG and Launch Templates responsibly  

---

## 🚀 Project Steps (Simplified)
1️⃣ Search for **EC2** and open the EC2 dashboard.  
2️⃣ Create a **Launch Template**, select Amazon Linux, t2.micro, and attach a key pair.  
3️⃣ Create an **Auto Scaling Group** using this Launch Template.  
4️⃣ Select multiple **Availability Zones** for high availability.  
5️⃣ Configure capacity — Desired capacity: 2, 
Minimum capacity: 2, 
Maximum capacity: 10.  
6️⃣ Review and create the Auto Scaling Group.  
7️⃣ Observe the **EC2 Instances** being created automatically.  
8️⃣ Monitor scaling behavior using the **ASG Activity** tab.

Full detailed steps with screenshots are available in the project documentation.

---

## 🌟 Key Features
- Automatic provisioning of EC2 instances  
- Multi-AZ configuration for reliability  
- Standardized deployments using Launch Templates  
- Capacity management for scaling operations  
- Activity-based monitoring of ASG behavior  
- Real-world introduction to scalable cloud architecture  

---

## 🧹 Cleanup
To avoid unnecessary cost:  
- Terminate EC2 instances created by the ASG  
- Delete the **Auto Scaling Group**  
- Delete the **Launch Template**  

---

## 🏁 Outcome
By completing this project, you learn how Auto Scaling Groups maintain performance and reliability by adjusting instance capacity automatically.  
This project builds your foundational understanding of **scaling**, **high availability**, and **resource efficiency** in AWS.  

---

## 🎥 Project Demo Video
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode6-aws-activity-7292414083839000576-30Ro

---

## 📄 Full Project Documentation
👉 https://www.linkedin.com/posts/khushi-nandwani_asg-project-documentation-activity-7292776459146805248-zcKz

---

## 🏷️ Tags
`AWS Auto Scaling` `Launch Templates` `EC2 Scaling` `High Availability` `Cloud Architecture`  
`AWS Networking` `Beginner–Intermediate AWS Project`

