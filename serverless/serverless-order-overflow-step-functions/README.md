# 🌀 Serverless Order Overflow Workflow (AWS Lambda + Step Functions)

## 📌 Project Level: Advanced
A production-style serverless workflow built using **AWS Step Functions**, **Lambda**, and **DynamoDB** to simulate real-world order processing.  
The workflow orchestrates multiple steps such as order validation, payment simulation, inventory checks, and final status updates, all using a fully serverless architecture.

This project demonstrates how complex application logic can be executed reliably using AWS-managed state machines.

---

## 📝 Project Overview
This project walks through designing and deploying a **serverless order-processing workflow** using AWS Step Functions.  
Each stage in the workflow is executed by a Lambda function, and the order status is maintained inside a DynamoDB table.

The Step Functions state machine handles branching logic, error handling, execution flow, and status transitions.  
If any step fails (e.g., payment failure, stock unavailability), the workflow automatically moves to a failure path.

This architecture closely mirrors real-world e-commerce order pipelines.

---

## 🎯 Objective
To build an automated, event-driven workflow where AWS Step Functions coordinate multiple Lambda functions to validate, process, and update customer orders in a DynamoDB table.

---

## 🧰 AWS Services Used
- **AWS Lambda** — Core business logic for validation, payment, inventory checks  
- **AWS Step Functions** — Orchestration and workflow state management  
- **Amazon DynamoDB** — Stores order details and workflow results  
- **IAM Roles** — Permissions for Step Functions ↔ Lambda ↔ DynamoDB  
- **CloudWatch Logs** — Debugging workflow execution and Lambda behavior  

---

## 🧠 What This Project Teaches
- Building Step Functions state machines  
- Integrating Lambda functions into workflow steps  
- Writing business logic for order processing  
- Handling success, failure, retry, and branching paths  
- Updating order status inside DynamoDB  
- Debugging workflow runs using the Step Functions console  
- Designing production-ready serverless workflows  

---

## 🚀 Project Steps (Simplified)
1️⃣ Create a **DynamoDB table** to store order details.  
2️⃣ Build Lambda functions to perform:  
   - Order validation  
   - Payment simulation  
   - Inventory check  
   - Order success/failure updates  

3️⃣ Create a **Step Functions state machine** and add each Lambda function as a workflow state.  
4️⃣ Define success, failure, and fallback transitions.  
5️⃣ Deploy and execute the workflow with sample order input.  
6️⃣ Monitor execution visually in the Step Functions console.  
7️⃣ Check DynamoDB to confirm final order status.  
8️⃣ Review CloudWatch Metrics and Logs for each Lambda stage.

Full detailed steps with screenshots are available in the project documentation.

---

## 🌟 Key Features
- Fully automated, serverless workflow  
- Multi-step orchestration with Step Functions  
- Realistic order lifecycle simulation  
- Built-in error handling and branching logic  
- DynamoDB-powered order storage  
- Modular Lambda-based architecture  
- Clear visualization of workflow execution  

---

## 🧹 Cleanup
To prevent unnecessary charges:

- Delete the Step Functions state machine  
- Delete all Lambda functions  
- Remove IAM roles/policies created for the workflow  
- Delete the DynamoDB table  
- Remove any CloudWatch log groups if desired  

---

## 🏁 Outcome
This project delivers a deep understanding of how to build **complex, event-driven, production-grade serverless applications**.  
You learn how Step Functions coordinate multiple Lambda functions into a structured workflow, a critical skill for backend cloud engineers.

---

## 🎥 Project Demo Video  
👉 **https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode15-aws-activity-7326511842598576128-xKk6**

---

## 📄 Full Project Documentation  
👉 **https://www.linkedin.com/posts/khushi-nandwani_serverless-order-flow-with-aws-lambda-and-activity-7326840925236731904-y0-G**

---

## 🏷️ Tags  
`AWS Step Functions` `Serverless Workflow` `Lambda` `DynamoDB`  
`Event-Driven Architecture` `Order Processing` `Advanced AWS Project`

