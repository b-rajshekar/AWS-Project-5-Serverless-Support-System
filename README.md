# Serverless Support System on AWS

This project is a simple **serverless support ticket system** built using AWS services.  
Users can submit a support request through a web form, and the data is processed and stored using serverless components.

---

## 🚀 Project Overview

- A static website allows users to submit support tickets
- The request is sent to an API Gateway endpoint
- AWS Lambda processes and validates the request
- The ticket data is stored in DynamoDB
- The application is fully serverless and scalable

---

## 🧱 Architecture

User  
→ CloudFront  
→ S3 (Static Website)  
→ API Gateway  
→ Lambda (Node.js)  
→ DynamoDB  

---

## 🛠️ AWS Services Used

- **Amazon S3** – Static website hosting  
- **Amazon CloudFront** – Content Delivery Network (CDN)  
- **Amazon API Gateway** – REST API for backend communication  
- **AWS Lambda** – Serverless backend logic (Node.js)  
- **Amazon DynamoDB** – NoSQL database for storing tickets  
- **AWS IAM** – Permissions and security  
- **Amazon CloudWatch** – Logs and monitoring  

---

## 📸 Screenshots

### 1️⃣ Support Form (Frontend)

<img width="1918" height="1013" alt="Screenshot 2026-01-05 073021" src="https://github.com/user-attachments/assets/3ea003eb-5888-4a3c-abbe-0c8c9c9cffb4" />


### 2️⃣ API Gateway Stage

<img width="1919" height="837" alt="image" src="https://github.com/user-attachments/assets/e823b934-0d03-4f6d-a654-d8f3a251db2f" />


### 3️⃣ Lambda Function

<img width="1897" height="916" alt="image" src="https://github.com/user-attachments/assets/e1efd6f6-04b0-4341-bb9c-a1cf48e33472" />


### 4️⃣ DynamoDB Table

<img width="1917" height="881" alt="image" src="https://github.com/user-attachments/assets/3f69ba10-7502-4026-af5a-0e3aafb47694" />


---

## ✅ Features

- Fully serverless architecture
- Input validation in Lambda
- CORS enabled for secure browser communication
- Scalable and cost-effective
- No servers to manage

---

## 🧪 How It Works

1. User submits the support form
2. API Gateway receives the request
3. Lambda validates the input
4. Ticket is stored in DynamoDB
5. Success response is returned to the user

---

## 🎯 What I Learned

- Building end-to-end serverless applications
- Handling CORS issues in API Gateway
- Debugging Lambda errors using CloudWatch
- Working with DynamoDB and IAM permissions
- Deploying and testing cloud-based systems

---

## 👤 Author

**Rajshekar**  
Aspiring Cloud / DevOps Engineer  
