# 🛒 Multi-Container eCommerce Deployment with Docker Compose

## 📌 Overview

This project demonstrates deployment of a full-stack eCommerce application using Docker Compose on Linux.

The stack includes frontend, backend APIs, databases, and reverse proxy services running in isolated containers.

---

## 🏗️ Architecture

* **Frontend** → Angular Client
* **Backend API 1** → Node.js Service
* **Backend API 2** → Java Spring Boot Service
* **Reverse Proxy** → Nginx
* **Database 1** → MongoDB
* **Database 2** → MySQL

---

## 🚀 Technologies Used

* Docker
* Docker Compose
* Linux
* Angular
* Node.js
* Java
* Nginx
* MongoDB
* MySQL

---

## ⚙️ How to Run

### Clone Repository

```bash id="h6p7jw"
git clone https://github.com/anyone0088/emart-microservices-docker-compose.git
cd docker_deployment
```

### Start Containers

```bash id="w2m8ve"
docker compose up -d
```

### Check Running Containers

```bash id="x9r3ku"
docker ps
```

### Stop Containers

```bash id="n4q1sa"
docker compose down
```

---

## 🌐 Access Application

Open in browser:

```text id="t5v2lm"
http://localhost
```

---

## 📚 Key Learnings

* Multi-container application deployment
* Docker networking between services
* Port mapping and browser access
* Troubleshooting container build issues
* Managing databases inside containers
* Real-world DevOps workflow

---

## 🎯 Future Improvements

* CI/CD pipeline integration
* Security scanning with Trivy
* Monitoring with Prometheus & Grafana
* Kubernetes deployment
* Cloud hosting (AWS / Azure)

---

## 👨‍💻 Author

Deepanshu Prabhakar
