
# 🔒 Fortifying AWS Security with Multi-Factor Authentication (MFA)

## 📌 **Project Level:** Beginner  
A security-focused AWS foundations project where you enable **Multi-Factor Authentication (MFA)** for the root account and IAM users to add an essential extra layer of protection to the AWS environment.

---

## 📝 **Project Overview**  
This project walks through enabling **MFA** on both the AWS **root account** and **IAM users**, using virtual authentication apps like Google Authenticator.  
It strengthens identity protection by requiring two verification steps—password + one-time MFA code—making unauthorized access far more difficult.

---

## 🎯 **Objective**  
To enhance AWS account security by enabling MFA for critical accounts and IAM users, ensuring that access to AWS resources requires both a password and a time-based one-time code.

---

## 🧰 **AWS Services & Tools Used**
- **AWS IAM** — Manage users, roles, and security credentials  
- **AWS Console Security Settings** — Root account MFA configuration  
- **Virtual MFA App** (Google Authenticator / Authy) — Generate TOTP codes  
- **AWS Login Console** — Verify MFA prompts  

---

## 🧠 **What This Project Teaches**
- Why MFA is important for cloud security  
- Differences between virtual, hardware, and SMS MFA  
- Enabling MFA on the root account  
- Assigning MFA to IAM users  
- Logging in with MFA-protected accounts  
- Understanding AWS security best practices  
- Testing and troubleshooting MFA  

---

## 🚀 **Project Steps (Simplified)**

1️⃣ **Open IAM and access Security Credentials** to start MFA setup for the root account.  

2️⃣ **Activate MFA** and choose a device type such as a virtual MFA app like Google Authenticator.  

3️⃣ **Scan the QR code** using your MFA app and enter two consecutive OTP codes to complete the setup.  

4️⃣ **Navigate to IAM → Users** and select the IAM user who should also be protected by MFA.  

5️⃣ **Enable MFA for the IAM user** by repeating the setup steps (choose device → scan QR code → enter OTP codes).  

6️⃣ **Test MFA login** by signing out and signing back into AWS, confirming you are prompted for an MFA code.  

7️⃣ **Verify successful configuration** by checking your IAM dashboard for the MFA badge next to each user.  

> Full screenshots, detailed steps, and MFA UI examples are available in the project documentation.

---

## 🌟 **Key Features**
- MFA enabled for both AWS root and IAM accounts  
- Stronger protection against credential theft  
- Practical understanding of TOTP-based MFA apps  
- Hands-on application of AWS security best practices  
- Ability to manage and verify MFA status across IAM users  

---

## 🧹 **Cleanup**
- Ensure backup MFA codes are saved securely  
- Remove old MFA devices if replaced  
- Review IAM users and confirm MFA is consistently enabled  

---

## 🏁 **Outcome**
This project reinforces secure authentication practices in AWS.  
By enabling MFA, you significantly reduce unauthorized access risks and align your cloud environment with standard industry security guidelines.

---

## 📄 **Full Project Documentation**
👉 https://www.linkedin.com/posts/khushi-nandwani_mfa-documentation-activity-7273573678317985792-5ije?utm_source=share&utm_medium=member_desktop&rcm=ACoAAE_UPJEBCVOHK7-Dy5jdozttNcasmFHJYAM

---

## 🏷️ **Tags**  
`AWS MFA` `IAM Security` `Identity Protection` `Cloud Security` `AWS Root Account` `Beginner AWS Project` `Authentication` `Best Practices`
