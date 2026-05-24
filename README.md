# 🚀 Day 21 – AWS Serverless Web Application

---

# 📌 Overview

On Day 21, I explored how to build a fully serverless web application using:

* AWS Lambda
* API Gateway
* DynamoDB
* S3 Hosting
* CloudWatch

This is one of the most powerful cloud-native architectures because there are:
✅ No servers to manage
✅ Automatic scaling
✅ Low operational cost
✅ High availability

---

# ☁️ What is Serverless Architecture?

Serverless architecture allows developers to build applications without managing servers.

AWS automatically handles:

* Infrastructure
* Scaling
* Availability
* Monitoring

---

# 🔑 Core AWS Services Used

| Service     | Purpose           |
| ----------- | ----------------- |
| Lambda      | Backend logic     |
| API Gateway | API management    |
| DynamoDB    | NoSQL database    |
| S3          | Frontend hosting  |
| CloudWatch  | Monitoring & logs |

---

# ⚙️ Serverless Workflow

```plaintext id="m7k2pw"
User
  ↓
S3 Static Website
  ↓
API Gateway
  ↓
AWS Lambda
  ↓
DynamoDB
  ↓
Response to User
```

---

# 🌐 Real-World Project – Student Portal Application

---

# 🏗️ Project Objective

Build a cloud-native student portal where:

* Frontend hosted in S3
* API Gateway receives requests
* Lambda processes backend logic
* DynamoDB stores student records
* CloudWatch monitors system

---

# 🧠 Architecture Diagram

```plaintext id="z5x9tv"
Users
   ↓
S3 Static Website
   ↓
API Gateway
   ↓
Lambda Functions
   ↓
DynamoDB Database
   ↓
CloudWatch Monitoring
```

---

# 🔐 Security Features

* IAM Roles
* HTTPS API access
* DynamoDB encryption
* Lambda permissions
* API throttling

---

# 📊 Monitoring & Logging

## CloudWatch Tracks:

* Lambda execution
* API requests
* Errors & latency
* DynamoDB usage

---

# 💻 Example Lambda Code

```python id="v6f2la"
import json

def lambda_handler(event, context):
    return {
        "statusCode": 200,
        "body": json.dumps("Serverless App Working!")
    }
```

---

# 🔟 Real-World Use Cases

1. Student portals
2. Banking applications
3. AI/ML APIs
4. Chat applications
5. SaaS products
6. Mobile app backend
7. IoT applications
8. Event-driven systems
9. Enterprise automation
10. Cloud-native startups

---

# 🧪 Hands-On Tasks

## Task 1

Create DynamoDB table.

---

## Task 2

Create Lambda function.

---

## Task 3

Configure API Gateway.

---

## Task 4

Host frontend in S3.

---

## Task 5

Monitor logs using CloudWatch.

---

# 🧠 What I Learned

* Serverless architecture
* Event-driven applications
* API Gateway integration
* Lambda + DynamoDB workflow
* Cloud-native scalability

---

# 🚀 Special Highlight

🔥 This architecture is heavily used in modern startups and scalable SaaS products.

---

# 📌 Author

**Sankar S**
Cloud & AI Learning Journey 🚀
