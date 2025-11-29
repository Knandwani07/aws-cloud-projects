# 🔄 Auto Scaling with Elastic Load Balancing (ASG + ALB)

## 📌 Project Level: Intermediate
A hands-on AWS project where you combine an **Auto Scaling Group (ASG)** with an **Application Load Balancer (ALB)** to build a scalable, fault-tolerant, and highly available architecture that automatically adjusts compute capacity based on demand.

This project demonstrates how AWS handles traffic distribution, scaling operations, and recovery during fluctuations in load.

---

## 📝 Project Overview
This project walks through creating a Launch Template, configuring an Auto Scaling Group, setting up an Application Load Balancer, and connecting everything through a Target Group.  
When demand increases, the ASG automatically launches new EC2 instances and the ALB distributes traffic across them. When demand decreases, the ASG scales down instances to reduce costs.

You also learn how health checks, scaling capacity, and multi-AZ distribution contribute to a highly available AWS architecture.

---

## 🎯 Objective
To build a dynamic, production-like architecture where an Auto Scaling Group launches EC2 instances on demand and an Application Load Balancer distributes traffic evenly across healthy targets.

---

## 🧰 AWS Services Used
- **Amazon EC2** — Compute instances for the application  
- **Launch Template** — Standardized instance configuration  
- **Auto Scaling Group (ASG)** — Automated scaling of EC2 instances  
- **Target Group** — Routing layer between ASG and ALB  
- **Application Load Balancer (ALB)** — Distributes traffic across instances  
- **Security Groups** — Control inbound/outbound traffic  

---

## 🧠 What This Project Teaches
- Creating and configuring a Launch Template  
- Deploying an Auto Scaling Group with multi-AZ support  
- Creating a Target Group for EC2 instance registration  
- Configuring an Application Load Balancer  
- Understanding health checks and instance lifecycle states  
- Observing automatic scaling events based on instance health  
- Monitoring traffic distribution and high availability  
- Cleaning up load balancers, ASGs, and EC2 resources correctly  

---

## 🚀 Project Steps (Simplified)
1️⃣ Create a **Launch Template** with AMI, instance type, user-data script, and key pair.  
2️⃣ Create a **Target Group** and configure health checks.  
3️⃣ Create an **Application Load Balancer**, attach security groups, and link it to the Target Group.  
4️⃣ Create an **Auto Scaling Group** using the Launch Template.  
5️⃣ Select two Availability Zones for high availability.  
6️⃣ Define capacity: Desired: 2, Min: 2, Max: 6.  
7️⃣ Link the ASG to the existing Target Group.  
8️⃣ Verify that EC2 instances launch and register with the ALB.  
9️⃣ Test the ALB DNS endpoint to ensure traffic is distributed across instances.

Full detailed steps with screenshots are available in the project documentation.

---

## 🌟 Key Features
- Fully automated scaling and load balancing  
- Multi-AZ fault-tolerant architecture  
- Traffic distribution across dynamic instances  
- Health-check based routing for reliability  
- Realistic production-grade setup  
- Improved performance and cost optimization  

---

## 🧹 Cleanup
To avoid unnecessary charges:
- Delete the Auto Scaling Group  
- Delete the Launch Template  
- Delete the Application Load Balancer  
- Delete the Target Group  
- Terminate any remaining EC2 instances  
- Remove unused security groups  

---

## 🏁 Outcome
This project gives you hands-on experience deploying a real-world scalable architecture that adjusts automatically to load changes.  
You learn how ASG and ALB work together to provide **high availability, elasticity, and performance**—key concepts for cloud engineers and DevOps roles.

---

## 🎥 Project Demo Video
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode7-aws-activity-7293508475295330304-2lnR

---

## 📄 Full Project Documentation
👉 https://www.linkedin.com/posts/khushi-nandwani_asg-elb-project-documentation-activity-7293863635280347136-_FB7

---

## 🏷️ Tags
`AWS Auto Scaling` `Application Load Balancer` `Target Groups` `High Availability`  
`Scalable Architecture` `EC2` `AWS Networking` `Intermediate AWS Project`

