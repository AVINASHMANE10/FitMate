# FitMate – Microservices-Based Fitness Platform

🚧 **Codebase Coming Soon**  
This repository is currently being prepared. The complete source code and setup instructions will be added soon.

FitMate is a **microservices-based fitness platform** designed to help users discover gyms, generate workout plans, track progress streaks, and explore fitness-related products — built using modern backend engineering practices.

---

## ✅ Project Overview

FitMate is built with **Spring Boot microservices** and focuses on scalability, modularity, and performance.  
It includes separate services for user management, gym recommendations, workouts, e-commerce, and streak tracking.

This project demonstrates:
- **Microservices architecture**
- **Secure REST APIs using JWT authentication**
- **Async communication using Kafka**
- **Low-latency streak tracking using Redis**
- **Containerization and deployment readiness using Docker/Kubernetes**

---

## 🧩 Microservices

| Service | Responsibility |
|--------|----------------|
| User Service | Authentication, user profiles, JWT token generation |
| Recommendation Service | Gym recommendations based on location & budget |
| Workout Service | Workout plan generation based on user goals |
| Streak Service | Tracks workout streaks using Redis |
| E-Commerce Service | Product listing and order management |
| API Gateway | Central routing + auth filter for services |

---

## 🏗️ Architecture Summary

- Client requests go through **API Gateway**
- API Gateway handles routing + authentication validation
- Services communicate via **REST** and **Kafka events**
- **Redis** is used for streak tracking to reduce DB hits and improve performance
- Data storage uses **MongoDB**

> 📌 Architecture diagram and docker-compose setup will be added with the code release.

---

## 🛠️ Tech Stack

**Backend**
- Java
- Spring Boot
- Spring Security (JWT)
- Spring Cloud Gateway *(if applicable)*

**Databases & Cache**
- MongoDB
- Redis

**Messaging**
- Apache Kafka

**DevOps**
- Docker
- Kubernetes (deployment-ready)

---

## 📌 Status

✅ README + project documentation available  
🚧 Source code coming soon  
🚧 API docs (Swagger) will be added with implementation  
🚧 Docker setup will be included in the first release

---

## 👨‍💻 Author

**Avinash Mane**  
- LeetCode: https://leetcode.com/u/avinashmane10/  
- HackerRank: https://www.hackerrank.com/profile/maneavinash818  

---

## 📄 License

This project will be released under the **MIT License**.
