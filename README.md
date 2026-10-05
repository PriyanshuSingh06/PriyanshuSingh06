<h1 align="center">Hey 👋 What's Up?</h1>

<div align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,mysql,postgres,aws,redis,docker,git,maven,kafka" height="60"/>
</div>

<br>

<div align="center">

<a href="https://linkedin.com/in/priyanshusingh06/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/PriyanshuSingh06">
  <img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:singh.priyanshu.work@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://www.instagram.com/_priyanshuu_06/">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
</a>

</div>

<br>

---

## 👨‍💻 About Me

Backend & Cloud Developer building real-world backend systems with **Java and Spring Boot**.

- ☕ Core Java & OOP fundamentals
- 🚀 Spring Boot REST APIs
- 🗄️ Spring Data JPA / Hibernate
- 🐘 PostgreSQL & MySQL
- ⚡ Apache Kafka & Event-Driven Architecture
- 🔗 Microservices
- ☁️ AWS Cloud
- 🐳 Docker
- 🏗️ System Design
- 💼 Preparing for Backend Developer Internships

---

## 🛠 Tech Stack

### 💻 Language

**Java**

### 🚀 Backend

**Spring Boot • Spring MVC • Spring Data JPA • Hibernate**

### 🗄️ Database

**PostgreSQL • MySQL • Redis**

### ⚡ Messaging & Architecture

**Apache Kafka • Microservices • Event-Driven Architecture**

### ☁️ Cloud

**AWS EC2 • AWS RDS • AWS S3**

### 🔧 Tools

**Maven • Git • Docker**

---

# 🚀 Featured Projects

## 💳 Advance Payment Gateway

A Spring Boot payment gateway prototype implementing a complete simulated payment lifecycle with **Kafka-based event-driven architecture** and a separate notification microservice.

### ✨ Features

- 💰 Payment creation and validation
- 🔑 Idempotency-Key support
- 🔄 Payment processing and retry mechanism
- 💳 Mock payment processor
- 🔁 Payment refund workflow
- 🧩 Payment state-machine validation
- 📊 Payment attempt tracking
- 📝 Transaction history and audit trail
- ⚡ Kafka payment status events
- 🔗 Separate PaymentNotificationService microservice
- 🔐 HMAC webhook signature verification
- 🛡️ Duplicate webhook protection
- 🗄️ PostgreSQL persistence
- 🛠️ Flyway database migrations
- ⚠️ Global exception handling
- ✅ Request validation

### 🔄 Payment Lifecycle

```text
CREATED
   ↓
PROCESSING
   ↓
SUCCESS ─────→ REFUNDING ─────→ REFUNDED
   │
   └──→ FAILED
          ↓
        RETRY
          ↓
      PROCESSING
```

### 🏗️ Architecture

```text
                    ┌──────────────────────┐
                    │      Client/API      │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │   Payment Gateway    │
                    │    Spring Boot       │
                    └──────────┬───────────┘
                               │
                    ┌──────────┴──────────┐
                    │                     │
                    ▼                     ▼
             ┌─────────────┐       ┌──────────────┐
             │ PostgreSQL  │       │    Kafka     │
             │             │       │payment-events│
             └─────────────┘       └───────┬──────┘
                                           │
                                           ▼
                              ┌──────────────────────┐
                              │ Payment Notification │
                              │       Service        │
                              └──────────────────────┘
```

### 🛠️ Tech Stack

**Java 26 • Spring Boot 4 • Spring Data JPA • PostgreSQL • Apache Kafka • Flyway • Maven**

---

## ☁️ AWS Cloud Deployment Project

Cloud deployment project focused on deploying a backend application using AWS infrastructure.

### ✨ Features

- ☁️ EC2 application deployment
- 🗄️ PostgreSQL database using RDS
- 🌐 VPC configuration
- 🔐 Security Groups
- 🔗 Cloud-based backend architecture

### 🛠️ Tech Stack

**AWS EC2 • AWS RDS • VPC • PostgreSQL**

---

## 🤖 AI Chatbot Project

AI chatbot project exploring **LLM and Retrieval-Augmented Generation** concepts.

### ✨ Features

- 🧠 LangChain integration
- 🤖 Llama-based local LLM
- 📚 Retrieval-Augmented Generation
- 💻 Local model inference
- 🖥️ Streamlit interface

### 🛠️ Tech Stack

**Python • LangChain • Llama • Streamlit**

---

# 📫 Connect With Me

<div align="center">

<a href="https://linkedin.com/in/priyanshusingh06/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/PriyanshuSingh06">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:singh.priyanshu.work@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://www.instagram.com/_priyanshuu_06/">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
</a>

</div>

<br>

<div align="center">

### 🚀 Building Backend Systems • Learning System Design • Growing with Java

</div>
