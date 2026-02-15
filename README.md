# ☕ CoffeeShop Manager – Serverless Inventory Management Backend

CoffeeShop Manager is a fully serverless inventory management system built using AWS services.  
The goal of this project is to design a lightweight, scalable, and cost‑efficient backend for coffee shop operations — with **no servers to manage**.

This architecture follows the **Performance Efficiency Pillar** of the AWS Well‑Architected Framework and demonstrates real-world serverless patterns using event-driven components, fine‑grained security, and modern frontend integration.

---

## 🚀 Project Overview

Traditional inventory systems rely on always‑on servers requiring manual maintenance, scaling, and monitoring.  
**CoffeeShop Manager takes a serverless‑first approach**, using:

- Amazon API Gateway  
- AWS Lambda & Lambda Layers  
- Amazon DynamoDB  
- AWS IAM  
- Amazon CloudWatch  
- AWS Amplify  
- React.js  

The result: A secure, highly scalable backend that automatically adjusts to traffic spikes while offering pay‑per‑use pricing.

---

## 👨‍💻 Your Role

As a Solutions Architect, you designed and deployed a real-world serverless application that is:

- Easy to manage  
- Event-driven  
- Secure with IAM policies  
- Fully monitored through CloudWatch  
- Cost-effective  
- Integrated with a modern frontend  

---

## 📚 What You’ll Learn

- Designing REST APIs with **API Gateway + Lambda**
- Building CRUD operations using **DynamoDB**
- Creating **Lambda Layers** for shared logic
- Implementing **IAM roles & policies**
- Enabling **CORS** for frontend interaction
- Deploying modern SPA frontend using **AWS Amplify**
- Monitoring logs, errors, and performance using **CloudWatch**
- Connecting frontend applications to serverless backends

---

## 🧠 System Flow

1. Coffee shop owner logs into the Amplify‑hosted React UI  
2. User views current coffee inventory (GET)  
3. Adds new coffee items (POST)  
4. Updates existing items (PUT)  
5. Removes sold‑out items (DELETE)  
6. React app calls API Gateway  
7. API Gateway triggers Lambda  
8. Lambda interacts with DynamoDB  

---

## 🛠 Technologies Used

- **DynamoDB** – Coffee inventory database  
- **Lambda Functions** – CRUD logic  
- **Lambda Layers** – Reusable utilities  
- **API Gateway** – REST API + CORS  
- **IAM** – Secure permissions  
- **CloudWatch** – Monitoring  
- **React.js** – Frontend  
- **AWS Amplify** – Hosting + CI/CD  

---

## ⏳ Time & Cost

- Estimated build time: **3–4 hours**  
- Cost: **$0.10–$0.50** (mostly free tier)

---

## 🏗 Architecture Diagram

<img src="./Architecture.png" alt="Project Architecture" width="800"/>

---

## 🧩 Final Features

By the end of this project, you have:

- A fully serverless backend  
- Complete CRUD inventory operations  
- Secure IAM‑based API integrations  
- Real‑time logging and metrics  
- Modern React UI hosted globally  
- Pay‑per‑use scalable infrastructure  
- Production‑ready architecture aligned with AWS best practices  

---

## 🧵 Steps Performed

1. **Infrastructure Setup** – DynamoDB & IAM  
2. **Lambda Layer + Functions** – Business logic  
3. **API Gateway** – REST endpoints  
4. **Frontend Development** – React + Amplify hosting  
5. **Cleanup & Resources**  

---


<img src="./coffee-site-image.png" alt="Front End View" width="800"/>

---
## 🎉 Conclusion

You’ve built a production‑grade serverless system that represents how modern cloud‑native applications operate today.

This project demonstrates:

- Serverless-first architecture  
- Operational excellence  
- Scalable and cost‑effective design  
- Real-world cloud engineering principles  

Perfect for your portfolio, cloud resume, or interview discussions.  
``