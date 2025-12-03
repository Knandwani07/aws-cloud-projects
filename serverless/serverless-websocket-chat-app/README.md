# 💬 Serverless WebSocket Chat Application (API Gateway + Lambda)

## 📌 Project Level: Advanced
A real-time serverless messaging application built using **API Gateway WebSocket APIs**, **AWS Lambda**, and **DynamoDB**.  
This project demonstrates event-driven communication, persistent connections, and serverless message routing without managing any servers.

It simulates how modern chat applications handle live messaging between multiple connected users.

---

## 📝 Project Overview
This project walks through creating a **WebSocket-based serverless backend** using Amazon API Gateway.  
You configure connection routes, integrate Lambda functions to manage connections and messages, and use DynamoDB to store active client connection IDs.

When users send messages, API Gateway triggers the Lambda function, which broadcasts the message to all connected clients — enabling fully real-time communication.

This setup demonstrates event-driven architecture, state handling, and real-time data flow in AWS.

---

## 🎯 Objective
To build a fully serverless WebSocket chat application capable of handling real-time messaging using API Gateway routes, Lambda functions, and DynamoDB storage.

---

## 🧰 AWS Services Used
- **Amazon API Gateway (WebSocket API)** — Manages real-time connections  
- **AWS Lambda** — Handles connect, disconnect, and message routing  
- **Amazon DynamoDB** — Stores active WebSocket connection IDs  
- **IAM Roles** — Allows Lambda to access API Gateway + DynamoDB  
- **CloudWatch Logs** — Monitors message activity and errors  

---

## 🧠 What This Project Teaches
- Creating a WebSocket API with `$connect`, `$disconnect`, and `$default` routes  
- Deploying Lambda functions for connection lifecycle management  
- Storing and retrieving connection IDs using DynamoDB  
- Broadcasting messages to connected WebSocket clients  
- Understanding real-time, event-driven communication patterns  
- Using IAM roles to allow Lambda to call API Gateway management APIs  
- Testing live chat functionality in the API Gateway console  
- Cleaning up serverless resources properly  

---

## 🚀 Project Steps (Simplified)
1️⃣ Create a WebSocket API in API Gateway with the routes:  
- `$connect`  
- `$disconnect`  
- `$default`

2️⃣ Create three Lambda functions to handle:  
- Storing connection IDs in DynamoDB  
- Removing connection IDs when users disconnect  
- Broadcasting messages to all connected users  

3️⃣ Create a DynamoDB table to store WebSocket connection IDs.  
4️⃣ Grant Lambda permissions to read/write DynamoDB + invoke API Gateway callback URLs.  
5️⃣ Deploy the WebSocket API and note the WebSocket endpoint URL.  
6️⃣ Use the **“Connect”** feature in API Gateway to simulate multiple clients.  
7️⃣ Send messages and observe real-time broadcast responses from Lambda.  
8️⃣ View logs in CloudWatch to verify message handling and connection events.

Full detailed steps with screenshots are available in the project documentation.

---

## 🌟 Key Features
- Fully serverless real-time chat functionality  
- WebSocket API supporting persistent two-way connections  
- DynamoDB-backed session and connection tracking  
- Lambda-powered message routing and broadcasting  
- Event-driven serverless architecture with no servers or containers  
- Highly scalable and cost-efficient communication model  

---

## 🧹 Cleanup
To avoid unnecessary charges:

- Delete the WebSocket API  
- Delete all deployed stages  
- Remove all Lambda functions  
- Delete the DynamoDB table  
- Remove IAM roles and policies if no longer needed  

---

## 🏁 Outcome
This project builds deep understanding of **real-time serverless architectures** on AWS.  
You learn how API Gateway WebSockets, Lambda, and DynamoDB work together to power scalable, stateful, event-driven applications, skills essential for advanced cloud and serverless engineering.

---

## 🎥 Project Demo Video
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode11-serverless-activity-7310895873138307072--6NF

---

## 📄 Full Project Documentation
👉 https://www.linkedin.com/posts/khushi-nandwani_serverless-chat-application-project-documentation-activity-7311258250077765633-d9tn

---

## 🏷️ Tags
`WebSocket API` `API Gateway` `Serverless` `DynamoDB` `Lambda`  
`Real-Time Messaging` `Event-Driven Architecture` `Advanced AWS Project`

