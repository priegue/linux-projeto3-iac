# 🐳 Docker Microservices – Nginx + PHP

Shell Script–based Docker project demonstrating a simple microservices-style web application using **Nginx** and **PHP**, developed as part of a DIO educational challenge.

---

## 📌 About the project
This project demonstrates the creation of a simple web application using **Docker**, **Nginx**, and **PHP**, organized into containers.

The goal is to apply fundamental **microservices concepts**, abstracting the runtime environment from the application itself and improving portability and reproducibility.

This challenge is inspired by the **Toshiro Shibakita** reference project, with personal adaptations and organization.

---

## 🧱 Architecture
- Docker container
- **Nginx** web server
- **PHP** application
- Custom Nginx configuration
- Base structure for microservices evolution

---

## 🛠 Technologies used
- Docker
- Nginx
- PHP
- Linux
- Git and GitHub

---

## 📂 Project structure
- Dockerfile        → Docker image build
- nginx.conf        → Nginx configuration
- index.php         → PHP application
- system_data.sql   → Sample data structure
- docs/             → Multi-language documentation

---

## ▶️ How to run

### Prerequisites
- Docker installed  
https://docs.docker.com/get-docker/

### Steps
```bash
1) Build the image:
docker build -t nginx-php-app .
2) Run the container:
docker run -p 8080:80 nginx-php-app
3) Access in your browser:
http://localhost:8080
```

# ⚠️ Important notes
- Project intended for study and lab environments
- Not recommended for production without security hardening
- Useful for understanding Docker and microservices fundamentals

---

## 📚 References
- Base repository (DIO):  
  https://github.com/denilsonbonatti/toshiro-shibakita

- Docker Docs:  
  https://docs.docker.com/

- Nginx Docs:  
  https://nginx.org/en/docs/

---

## 📄 License
Free project for study and modification.

---

## ⭐ About this repository

This project is part of my **Docker, Linux, and DevOps learning portfolio**, developed during my ongoing studies and continuous practice with containers and application architecture.

### ✔ Skills applied
- Docker containerization
- Introductory microservices concepts
- Nginx web server
- PHP applications in containers
- Project organization for portfolio
- Git version control
- Technical documentation

Project developed for educational and portfolio purposes.

