# ⚡ Event-Driven Automation with Amazon EventBridge  
## 📌 Project Level: Intermediate  

A hands-on AWS automation project where you use **Amazon EventBridge** to trigger a **Lambda function** based on scheduled events.  
This project demonstrates how serverless, event-driven architectures automate tasks without any manual intervention or server management.

You build a workflow where EventBridge generates events based on a schedule (every 5 minutes, hourly, daily, etc.) and forwards them to a Lambda function that processes the event automatically.

---

## 📝 Project Overview  
This project walks through creating an **EventBridge rule**, configuring a **cron/schedule expression**, setting a **Lambda function** as the target, and verifying automated execution using CloudWatch Logs.

You learn how EventBridge acts as the central event router in AWS, enabling automated workflows such as log processing, periodic cleanup, scheduled notifications, and serverless maintenance tasks.

---

## 🎯 Objective  
To automate the execution of a Lambda function using Amazon EventBridge by creating a scheduled event rule that triggers the function at a defined interval.

---

## 🧰 AWS Services Used  
- **Amazon EventBridge** — Event routing & scheduled triggers  
- **AWS Lambda** — Serverless compute executed by events  
- **Amazon CloudWatch Logs** — Verifying Lambda execution  
- **AWS IAM** — Permissions for EventBridge to invoke Lambda  

---

## 🧠 What This Project Teaches  
- Creating scheduled EventBridge rules (rate & cron expressions)  
- Connecting EventBridge to Lambda as a target  
- Understanding event-driven automation patterns  
- Inspecting event payloads passed from EventBridge  
- Monitoring Lambda executions in CloudWatch Logs  
- Designing workflows without servers or manual triggers  

Examples of tasks EventBridge can automate:
- Nightly data cleanup  
- Automated reporting  
- Serverless maintenance scripts  
- DNS health checks  
- Rotating files or logs  

---

## 🚀 Project Steps (Simplified)

1. Open **Amazon EventBridge** and create a new Rule.  
2. Choose **Schedule** and configure the frequency (e.g., every 2 minutes).  
3. Select **Lambda function** as the target.  
4. Give EventBridge permission to invoke the Lambda function.  
5. Save the rule and wait for the next scheduled event.  
6. Open **CloudWatch Logs** → verify that Lambda is being invoked automatically.  
7. Review event payloads and confirm automation behavior.

Full detailed steps with screenshots are available in the project documentation.

---

## 🌟 Key Features  
- Fully serverless automation workflow  
- Zero administration or cron servers required  
- Precise scheduling using cron or rate expressions  
- Event-driven Lambda execution  
- Real-time observability via CloudWatch Logs  
- Practical introduction to EventBridge as an automation engine  

---

## 🧹 Cleanup  
To avoid unintended Lambda invocations:

- Disable or delete the EventBridge rule  
- Delete the Lambda function (if no longer needed)  
- Remove CloudWatch Log Groups (optional)  

---

## 🏁 Outcome  
By completing this project, you gain hands-on experience building **event-driven automation** using EventBridge and Lambda.  
You learn how scheduled events trigger serverless functions, enabling automated workflows without servers, scripts, or manual triggers an essential skill in modern cloud and DevOps environments.

---

## 🎥 Project Demo Video  
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode18-aws-activity-7336625431552356352-6n0F  

---

## 📄 Full Project Documentation  
👉 https://www.linkedin.com/posts/khushi-nandwani_eventbridge-project-documentation-activity-7337730975570812928-8Ipn  

---

## 🏷️ Tags  
`Amazon EventBridge` `AWS Lambda` `Event-Driven Automation` `Serverless Architecture`  
`CloudWatch Logs` `Cron Jobs` `Intermediate AWS Project` `Automation`
