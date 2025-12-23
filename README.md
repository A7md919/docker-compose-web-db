# Docker Compose Web and Database Application

## 📌 Project Overview
This project demonstrates a **multi-container application** using **Docker Compose**, consisting of a web server (Nginx) and a MySQL database.  
It showcases container networking, persistent storage using volumes, and service dependencies.

---

## 🛠 Technologies Used
- Docker
- Docker Compose
- Nginx
- MySQL
- Linux
- HTML

---

## 📂 Project Structure

.
├── docker-compose.yml
├── html/
│ └── index.html
└── README.md


---

## 🚀 How to Run the Project

### 1️⃣ Start Services
```bash
docker compose up -d
```
### 2️⃣ Verify Containers
```bash
docker compose ps
```
### 3️⃣ Access Web Application
```bash
http://localhost:8081
```
## 💾 Persistent Storage
MySQL data is stored using Docker volumes to ensure data persistence even if containers are restarted.
## 🎯 Learning Outcomes
Deploying multi-container applications

Managing container networking

Using Docker volumes for persistent data

Understanding service dependencies in Docker Compose
## 👤 Author
Ahmed Ali Ahmed Mohamed
GitHub: https://github.com/A7md919
