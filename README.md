# 🚀 onvNotify  

A **serverless notification system** that allows users to send **emails** and **SMS messages** directly from a website using **AWS services**.  

This project demonstrates how to design an event-driven cloud workflow with **S3, API Gateway, Lambda, Step Functions, SES, and SNS**.  

---

## 📌 Features  
- 🌐 **Website Integration** – Trigger notifications (email/SMS) from a frontend hosted in S3.  
- ⚡ **Serverless Architecture** – Fully event-driven with AWS Step Functions orchestrating the workflow.  
- 📩 **Email Sending** – Implemented via AWS SES and Lambda.  
- 📱 **SMS Sending** – Implemented via AWS SNS and Lambda.  
- 🔄 **Workflow Management** – Step Functions to coordinate the execution of Lambda tasks.  

---

## 🛠️ Tech Stack  
- **AWS S3** – Hosting static website & storing inputs  
- **AWS API Gateway** – RESTful API trigger  
- **AWS Lambda** – Functions for handling requests and sending messages  
- **AWS Step Functions** – Orchestration of workflow execution  
- **AWS SES** – Email sending  
- **AWS SNS** – SMS sending  

---

## 📂 Project Structure  
<img width="1422" height="687" alt="Infrastructure" src="https://github.com/user-attachments/assets/a3e307b6-c655-421d-9277-6719351e5fda" />
