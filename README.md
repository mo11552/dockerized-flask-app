# Dockerized Flask Web App (CI/CD + Docker Hub)

## 📌 Overview
This project demonstrates containerizing a Python Flask application using Docker and automating builds using GitHub Actions.

---

## 🚀 Technologies Used
- Docker
- Python (Flask)
- GitHub Actions (CI/CD)

---

## 🐳 Docker Hub Image
https://hub.docker.com/r/moyo15/dockerized-flask-app

---

## ⚙️ Features
- Dockerized Flask application
- Automated image builds via CI/CD pipeline
- Public image available on Docker Hub

---

## ▶️ How to Run

### 1. Pull the image

docker pull moyo15/dockerized-flask-app:latest


### 2. Run the container

docker run -p 8080:8080 moyo15/dockerized-flask-app:latest


### 3. Open in browser

http://localhost:8080


---

## 🔄 CI/CD Pipeline
- Triggered on code push
- Builds Docker image
- Validates container build process

---

## 🎯 Key Features
- Containerized application deployment
- Automated CI/CD workflow
- Reusable Docker image

---

## 📌 Future Improvements
- Push images automatically to Docker Hub via CI/CD
- Add testing stage to pipeline