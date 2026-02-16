# 🤖 ChatOpsBot – Real-Time AWS Operations from Slack (Operational Excellence)

ChatOpsBot is a real-time DevOps automation system that brings AWS monitoring, alerting, and recovery actions directly into Slack.  
Engineering teams no longer need to jump between AWS Console, CloudWatch dashboards, and CLI tools — everything happens where your team already collaborates.

This architecture follows the **Operational Excellence Pillar** of the AWS Well‑Architected Framework and demonstrates how modern teams reduce response time, automate workflows, and stay informed using ChatOps patterns.

---

## ☁️ Project Overview

### 🎯 Scenario
ChatOpsBot allows your team to:

- Receive CloudWatch alarms directly in Slack  
- Trigger operational tasks like restarting services  
- Run secure AWS commands through IAM-controlled permissions  
- Use Slack as a real-time operational dashboard  

By integrating AWS Chatbot, Lambda, EventBridge, IAM, and CloudFormation, you build a secure and auditable system that improves visibility and drastically reduces mean time to recovery (MTTR).

---

## 👨‍💻 Your Role

As a Solutions Architect, your mission was to design a system that:

- Connects Slack with AWS using AWS Chatbot  
- Automates operational tasks  
- Provides real-time, actionable alerts  
- Enforces proper security through IAM  
- Uses infrastructure as code via CloudFormation  

---

## 📘 What You Learned

- Integrating **Slack with AWS Chatbot**
- Creating **CloudWatch alarms** for operational alerts
- Routing events using **EventBridge**
- Automating tasks with **Lambda** or **SSM documents**
- Managing access through **IAM roles**
- Deploying reproducible infrastructure using **CloudFormation**
- Hosting a frontend dashboard using **S3 + CloudFront**

---

## 👩‍💻 Steps Performed

### 1️⃣ Connect Slack with AWS Chatbot  
- Added Slack workspace  
- Configured permissions  
- Enabled AWS CLI commands from Slack

### 2️⃣ Create Lambda Functions / SSM Documents  
- Built sample task automation  
- Enabled Slack-to-Lambda command execution

### 3️⃣ Set Up Real-Time CloudWatch Alerts  
- Created a CPU Utilization alarm  
- Routed alerts to Slack via EventBridge and Chatbot

### 4️⃣ Configure IAM for Safe Access  
- Created temporary and limited-permission roles  
- Ensured only specific actions can run from Slack

### 5️⃣ Deploy Dashboard via CloudFormation  
- Used CloudFormation to deploy S3 + CloudFront  
- Enabled read-only dashboards for team visibility

---

## 🛠 Services Used

- **AWS Chatbot** – Slack integration  
- **Amazon CloudWatch** – Monitoring & alarms  
- **AWS Lambda / SSM** – Automated tasks  
- **Amazon EventBridge** – Event routing  
- **IAM** – Command/control permissions  
- **AWS CloudFormation** – IaC deployment  
- **Amazon S3 + CloudFront** – Dashboard hosting  

---

## ⏳ Estimated Time & Cost

- Time: **3–4 hours**  
- Cost: **$0.10–$0.50** (almost free)

---

## 🏗 Architectural Diagram

<img src="./Architecture.png" alt="Project Architecture" width="800"/>

---

## ⭐ Final Result

By the end of this project, you built a fully working real-time ChatOps system with:

- Slack notifications for AWS alarms  
- One-click operational fixes  
- Secure IAM-controlled actions  
- An optional read-only dashboard  
- Automated, auditable CloudFormation deployments  

This project showcases **Operational Excellence** in a real engineering workflow — automated, fast, transparent, and team-friendly.


<img src="./ChatBots-Dashboard.gif" alt="ChatBot Dashboard" width="800"/>
---

## 🎉 Conclusion

You've built more than just a Slack bot — you’ve engineered a real-time operational workflow used by modern engineering teams. Your system:

- Connects Slack to AWS Chatbot  
- Sends CloudWatch alarms directly to Slack  
- Automates fixes through Lambda or SSM  
- Uses IAM for secure, restricted permissions  
- Deploys a dashboard using CloudFormation  
- Demonstrates real-world ChatOps patterns  

This is a production-ready foundation for real ChatOps deployments.

---

## 🧹 Cleanup Steps

To avoid extra AWS costs:

1. **Delete Chatbot Slack configuration**  
2. **Delete IAM roles**  
3. **Remove CloudWatch alarms**  
4. **Terminate EC2 test instance**  
5. **Delete Lambda functions + CloudWatch Logs**  
6. **Delete S3 bucket + CloudFront distribution**  
7. **Delete CloudFormation stack**  

---

## 📄 License  
MIT License  