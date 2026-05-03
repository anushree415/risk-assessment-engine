# 🚀 Risk Assessment Engine

## 📌 Overview
A Spring Boot backend application to manage and analyze risk records with scoring, categories, and statuses.

---

## 🏗️ Architecture

Swagger UI → Spring Boot Backend → Database (H2/PostgreSQL) → Redis Cache

---

## ⚙️ Tech Stack
- Java 17
- Spring Boot
- Spring Data JPA
- Spring Security
- Redis
- H2 / PostgreSQL
- Swagger
- Docker

---

## 📋 Prerequisites
- Java 17+
- Maven
- Docker
- Git

---

## 🔧 Setup Steps

1. Clone repository
   git clone https://github.com/anushree415/risk-assessment-engine.git

2. Go to backend
   cd backend

3. Build project
   mvn package -DskipTests

4. Run with Docker
   docker compose up --build

---

## 🌐 Access

Swagger UI:
http://localhost:8080/swagger-ui/index.html

H2 Console:
http://localhost:8080/h2-console

---

## 🌱 Data Seeding
- 30 demo records auto-created
- Includes all statuses and categories

---

## 🔐 Environment Variables

| Variable | Description |
|---------|------------|
| DB_URL | Database URL |
| DB_USER | DB username |
| DB_PASSWORD | DB password |
| JWT_SECRET | Secret key |
| MAIL_USERNAME | Email |
| MAIL_PASSWORD | Password |

---

## 📁 Structure

backend/
 ├── controller/
 ├── service/
 ├── repository/
 ├── entity/
 ├── config/

---

## 🐳 Docker
- Runs on port 8080
- Fully containerized

---

## ✅ Status
- Backend working
- Swagger working
- Docker working
- Data seeding done

---

## 👩‍💻 Author
Anushree D
