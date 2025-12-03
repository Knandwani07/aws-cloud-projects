# 💥 Stress Testing EC2 & Monitoring with CloudWatch Alarms

## 📌 Project Level: Intermediate
A hands-on AWS project where you create a **stress environment** on an EC2 instance, monitor CPU utilization in real time using **Amazon CloudWatch**, and configure **CloudWatch Alarms** with **SNS notifications** to alert you when usage crosses defined thresholds.

This project builds practical understanding of cloud monitoring, alerting, and performance testing.

---

## 📝 Project Overview
This project demonstrates how to launch a Linux EC2 instance, install a stress tool, and generate high CPU usage to simulate a real-world load scenario.  
You then configure a CloudWatch Alarm that triggers when CPU usage exceeds a threshold (e.g., 70%) and sends an SNS email notification.

This helps you understand AWS monitoring at a fundamental level, how AWS reacts to resource stress, how alarms behave, and how notifications are sent.

---

## 🎯 Objective
To simulate heavy load on an EC2 instance using stress commands, monitor the instance with CloudWatch metrics, and create an automated CloudWatch Alarm that sends an SNS email alert when CPU utilization crosses the threshold.

---

## 🧰 AWS Services Used
- **Amazon EC2** — Create a Linux instance and run stress tests  
- **Security Groups** — Allow SSH access for terminal operations  
- **Amazon CloudWatch** — Monitor CPU utilization and configure alarms  
- **Amazon SNS** — Send email notifications when alarms trigger  

---

## 🧠 What This Project Teaches
- Launching and connecting to a Linux EC2 instance  
- Installing the stress utility to generate CPU load  
- Executing stress commands to simulate high CPU usage  
- Monitoring real-time CPU metrics in CloudWatch  
- Creating and configuring CloudWatch Alarms  
- Setting up an SNS Topic for email alerts  
- Verifying alarm state changes (OK → ALARM → OK)  
- Cleaning up CloudWatch, SNS, and EC2 resources safely  

---

## 🚀 Project Steps (Simplified)

1️⃣ Launch a Linux EC2 instance and connect using EC2 Instance Connect or SSH.  
2️⃣ Install the **stress tool** using package manager commands.  
3️⃣ Run a CPU stress test using a stress command to push CPU usage above 70%.  
4️⃣ Open CloudWatch → Metrics → EC2 → View CPUUtilization metric.  
5️⃣ Create a **CloudWatch Alarm** that triggers when CPU > 70% for a fixed period.  
6️⃣ Create an **SNS Topic**, subscribe your email, and confirm subscription.  
7️⃣ Trigger the alarm by running the stress command again.  
8️⃣ Watch for the ALARM state change and verify the SNS email notification.

Full detailed steps with screenshots are available in the project documentation.

---

## 🌟 Key Features
- Real-world simulation of high CPU load  
- CloudWatch metrics and monitoring fundamentals  
- Automated alerting using CloudWatch + SNS  
- Complete visibility into EC2 performance  
- Hands-on understanding of alarm thresholds and state transitions  
- Beginner-friendly introduction to cloud monitoring & alert automation  

---

## 🧹 Cleanup
To avoid unnecessary cost or unwanted alerts:
- Terminate the EC2 instance  
- Delete the CloudWatch Alarm  
- Delete the SNS Topic and unsubscribe the email  
- Remove security groups if not needed  

---

## 🏁 Outcome
By completing this project, you gain practical experience in:
- Monitoring EC2 performance  
- Simulating real workload conditions  
- Creating proactive alerting systems using CloudWatch and SNS  

This builds a strong foundation in **cloud monitoring, alerting, and operational awareness** skills essential for AWS engineers and DevOps roles.

---

## 🎥 Project Demo Video
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode8-aws-activity-7297487503136055299-_sNP

---

## 📄 Full Project Documentation
👉 https://www.linkedin.com/posts/khushi-nandwani_linux-stress-environment-project-documentation-activity-7297849891953729536-6L4E

---

## 🏷️ Tags
`AWS CloudWatch` `SNS Notifications` `EC2 Monitoring` `Stress Testing`  
`High CPU Utilization` `Cloud Operations` `Beginner–Intermediate AWS Project`


