# 🔌 Launching a Linux Machine on AWS Using PuTTY

## 📌 **Project Level:** Beginner  
A hands-on AWS project that shows how to launch a **Linux EC2 instance**, convert key pairs using **PuTTYgen**, and securely connect to the instance using **PuTTY** on Windows.  
Perfect for beginners learning SSH, EC2, and basic Linux operations.

---

## 📝 **Project Overview**  
This project walks through the complete process of launching a Linux EC2 instance on AWS and connecting to it using PuTTY, including converting PEM keys to PPK format, setting up SSH authentication, logging in, and verifying connectivity by running basic Linux commands.

---

## 🎯 **Objective**  
To deploy a Linux EC2 instance, convert the AWS key pair, connect using PuTTY, perform basic Linux operations, and terminate the instance securely after use.

---

## 🧰 **AWS Services & Tools Used**
- **Amazon EC2** — Launch and manage Linux servers  
- **Security Groups** — Control SSH access  
- **PuTTY** — SSH client for Windows  
- **PuTTYgen** — Converts `.pem` key to `.ppk` format  

---

## 🧠 **What This Project Teaches**
- Launching a Linux EC2 instance  
- Creating and converting key pairs  
- Understanding SSH authentication  
- Connecting to Linux machines via PuTTY  
- Running basic Linux commands (`sudo`, `mkdir`, `cat`)  
- Cleaning up cloud resources  

---

## 🚀 **Project Steps (Simplified)**

1️⃣ **Open AWS EC2 and launch a Linux instance** by selecting an AMI, choosing t2.micro, creating a key pair, and configuring a security group that allows SSH.  

2️⃣ **Download the key pair and convert the PEM file to PPK** using PuTTYgen so PuTTY can authenticate the SSH connection.  

3️⃣ **Open PuTTY and enter your instance's Public IP**, then load the converted `.ppk` private key under SSH → Auth.  

4️⃣ **Connect to your EC2 instance using PuTTY**, accept the security prompt, and log in with the default username (e.g., `ec2-user` or `ubuntu`).  

5️⃣ **Run basic Linux commands** such as switching to superuser, creating directories, and creating files to verify proper connection and functionality.  

6️⃣ **Exit PuTTY and terminate the EC2 instance** to avoid ongoing AWS charges.  

> More detailed instructions and screenshots are available in the project documentation.

---

## 🌟 **Key Features**
- Complete end-to-end SSH setup workflow  
- Practical use of PuTTY & PuTTYgen for Windows SSH access  
- Successfully connected to a cloud-based Linux machine  
- Verified connectivity using Linux commands  
- Built foundational understanding of authentication and EC2 setup  

---

## 🧹 **Cleanup**
- Close the PuTTY session  
- Terminate the EC2 instance  
- Delete unused key pairs if not required  

---

## 🏁 **Outcome**
You gain confidence in launching and accessing cloud-based Linux machines, understanding SSH authentication, and managing EC2 resources essential skills for AWS, DevOps, and cloud engineering.

---

## 🎥 **Project Demo Video**
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode4-aws-activity-7289877351990001666-llna?utm_source=share&utm_medium=member_desktop&rcm=ACoAAE_UPJEBCVOHK7-Dy5jdozttNcasmFHJYAM

---

## 📄 **Full Project Documentation**
👉 https://www.linkedin.com/posts/khushi-nandwani_linux-with-putty-project-documentation-activity-7290239757467439104-TbjS?utm_source=share&utm_medium=member_desktop&rcm=ACoAAE_UPJEBCVOHK7-Dy5jdozttNcasmFHJYAM

---

## 🏷️ **Tags**  
`AWS EC2` `PuTTY` `PuTTYgen` `Linux Server` `SSH` `Cloud Foundations` `Beginner AWS Project` `EC2 Connectivity` `Windows SSH`

