# 🚀 DevOps Flask Application

A simple Flask web application containerized using Docker and automated with GitHub Actions CI/CD.

## 🛠️ Tech Stack

- Python
- Flask
- Git & GitHub
- Docker
- Docker Hub
- GitHub Actions
- CI/CD

## 📌 Project Overview

This project demonstrates how a Flask application can be containerized using Docker and integrated with a CI/CD pipeline using GitHub Actions.

Whenever changes are pushed to the GitHub repository, GitHub Actions automatically builds the Docker image and publishes it to Docker Hub.

## 🔄 CI/CD Workflow

```text
Developer
   ↓
Git Push
   ↓
GitHub Repository
   ↓
GitHub Actions
   ↓
Build Docker Image
   ↓
Push Image to Docker Hub
   ↓
Run Docker Container
   ↓
Flask Application