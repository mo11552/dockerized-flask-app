# Dockerized Flask Web App

## 📌 Overview

This project is a simple Python Flask web application containerized using Docker. It demonstrates how applications can be packaged for consistent deployment across different environments.

## 🛠 Tech Stack

* Python
* Flask
* Docker

## 🚀 Run the Application

### Build Docker Image

docker build -t dockerized-flask-app .

### Run Container

docker run -p 8080:8080 dockerized-flask-app

## 🌐 Endpoints

* `/` → Returns a welcome message
* `/how-are-you` → Returns a status response

## 🎯 Purpose

Built to practice containerization and understand how applications are deployed in a DevOps workflow.

## 📦 Future Improvements

* Add CI/CD pipeline using GitHub Actions
* Deploy to AWS EC2
* Push image to Docker Hub
