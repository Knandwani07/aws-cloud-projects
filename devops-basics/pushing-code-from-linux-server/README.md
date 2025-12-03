# 🚀 Pushing Code to GitHub from a Linux Server (Secure Workflow)
📌 **Project Level: Beginner–Intermediate**  
A hands-on DevOps project where you configure Git on a Linux server, set up SSH authentication, and securely push code to GitHub without exposing passwords or tokens.  
This workflow is essential for cloud engineers, EC2 workflows, and secure automation pipelines.

---

## 📝 Project Overview
This project walks through installing Git on Linux, generating SSH keys, connecting them to GitHub, cloning repositories securely, and pushing code using SSH authentication.

You learn how to build a professional, secure Git workflow directly from a Linux server crucial for DevOps, automation, and cloud development.

---

## 🎯 Objective
To configure secure SSH-based Git authentication on a Linux server and push code to a GitHub repository without using passwords or personal access tokens.

---

## 🧰 Tools & Technologies Used
- **Linux Server (EC2 or local VM)** — Development environment  
- **Git** — Version control  
- **OpenSSH** — Secure authentication  
- **GitHub** — Remote repository hosting  

---

## 🧠 What This Project Teaches
- Installing Git on Linux  
- Generating SSH key pairs (ed25519 recommended)  
- Adding SSH public keys to GitHub  
- Cloning repositories via SSH  
- Staging, committing, and pushing code  
- Managing Git remotes  
- Secure DevOps workflow best practices  

---

## 🚀 Project Steps (Simplified)
1️⃣ Install Git (`sudo apt install git` or `sudo yum install git`)  
2️⃣ Generate SSH keys:  
`ssh-keygen -t ed25519 -C "email@example.com"`  
3️⃣ View the public key:  
`cat ~/.ssh/id_ed25519.pub`  
4️⃣ Add the public key to GitHub → *Settings → SSH and GPG Keys*  
5️⃣ Test the connection:  
`ssh -T git@github.com`  
6️⃣ Clone the repo using SSH:  
`git clone git@github.com:user/repo.git`  
7️⃣ Make changes, then run:  
`git add .`  
`git commit -m "Updated files"`  
8️⃣ Push to GitHub:  
`git push origin main`

For full details, refer to the project demo video.

---

## 🌟 Key Features
- Secure code push workflow from Linux  
- No tokens or passwords needed  
- End-to-end Git configuration  
- SSH-based authentication  
- DevOps-ready workflow  
- Ideal for EC2, on-prem Linux, or cloud automation  

---

## 🧹 Cleanup
To maintain security:
- Remove unused SSH keys from GitHub  
- Delete private keys from old servers  
- Restrict `.ssh` permissions (`chmod 600`)  
- Revoke compromised keys immediately  

---

## 🏁 Outcome
By the end of this project, you gain real experience pushing code from Linux using secure SSH authentication.  
This builds strong DevOps fundamentals for CI/CD pipelines, automation, and cloud engineering.

---

## 🎥 Project Demo Video
👉 https://www.linkedin.com/posts/khushi-nandwani_devopschronicles-episode14-github-activity-7323949554213543936-NVk1

---

## 🏷️ Tags
`Git` `GitHub` `SSH` `Linux` `DevOps` `Secure Workflow` `Remote Development` `Automation` `Beginner AWS Project` `CI/CD Basics`

