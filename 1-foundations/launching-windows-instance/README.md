# 🪟 Launching a Windows Instance on AWS

## 📌 **Project Level:** Beginner  
A practical AWS foundations project where you launch a **Windows EC2 instance**, configure key pairs, decrypt the administrator password, and securely connect using **RDP (Remote Desktop Protocol)**.  
Perfect for beginners learning Windows Server setup on AWS.

---

## 📝 **Project Overview**  
This project demonstrates how to deploy a **Windows Server instance** on AWS, configure networking and key pairs, retrieve the administrator password, connect via RDP, and finally terminate the instance to avoid extra charges.

---

## 🎯 **Objective**  
To launch, access, and manage a Windows Server instance on AWS using RDP by securely creating key pairs and decrypting the administrator password.

---

## 🧰 **AWS Services & Tools Used**
- **Amazon EC2** — Launch and manage Windows servers  
- **Security Groups** — Allow RDP (port 3389)  
- **Key Pair (.pem)** — Required to decrypt the Windows admin password  
- **RDP Client** — Connect to the Windows instance  

---

## 🧠 **What This Project Teaches**
- Launching Windows instances on AWS  
- Selecting Windows AMIs and instance types  
- Creating and using key pairs  
- Decrypting the Windows administrator password  
- Using RDP to connect to cloud-hosted Windows machines  
- Properly terminating resources to manage costs  

---

## 🚀 **Project Steps (Simplified)**

1️⃣ **Access the EC2 service** and navigate to the Instances page to begin launching a Windows Server.  

2️⃣ **Launch a new Windows instance** by selecting a Windows AMI, choosing `t3.micro` (Free Tier eligible), and entering a name.  

3️⃣ **Create a new key pair (.pem file)** to decrypt the Windows admin password later and download it securely to your system.  

4️⃣ **Configure networking and security groups**, ensuring RDP (port 3389) is allowed for remote access.  

5️⃣ **Launch the instance** and wait for it to pass all health checks before connecting.  

6️⃣ **Open RDP Client**, download the `.rdp` file from AWS, and retrieve the administrator password by decrypting it with your `.pem` key.  

7️⃣ **Connect via Remote Desktop** using the public IP, admin username, and decrypted password.  

8️⃣ **Terminate the Windows instance** once your tasks are complete to avoid AWS billing.

> Detailed screenshots for each step appear in your project documentation.

---

## 🌟 **Key Features**
- Complete Windows Server deployment using AWS EC2  
- Secure access setup using key pairs and decryption workflow  
- RDP-based access for GUI-style Windows administration  
- Beginner-friendly but practical real-world cloud compute example  
- Reinforces AWS access security and resource management  

---

## 🧹 **Cleanup**
- Terminate the Windows instance  
- Delete unused key pairs  
- Remove security groups if they were created for this project  

---

## 🏁 **Outcome**
This project provides hands-on experience launching and connecting to a Windows environment in AWS.  
You learn how to work with key pairs, decrypt credentials, use RDP, and safely manage compute resources — essential knowledge for cloud beginners.

---

## 🎥 **Project Demo Video**
👉 https://www.linkedin.com/posts/khushi-nandwani_console-home-console-home-eu-north-1-activity-7255567986311184384-nkd7?utm_source=share&utm_medium=member_desktop&rcm=ACoAAE_UPJEBCVOHK7-Dy5jdozttNcasmFHJYAM

---

## 📄 **Full Project Documentation**
👉 https://www.linkedin.com/posts/khushi-nandwani_aws-cloudcomputing-windowsserver-activity-7255851812472213504-AdxJ?utm_source=share&utm_medium=member_desktop&rcm=ACoAAE_UPJEBCVOHK7-Dy5jdozttNcasmFHJYAM

---

## 🏷️ **Tags**  
`AWS EC2` `Windows Server` `RDP` `Key Pair` `Cloud Foundations` `Beginner AWS Project` `Remote Desktop` `Windows Instance`

