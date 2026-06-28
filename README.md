# 🚀 Docker Test App

A simple Dockerized application for learning Docker image creation, container management, and deployment.

## 📋 Prerequisites

* Docker installed
* Git installed (optional)

## 📁 Project Structure

```text
docker-testapp/
├── Dockerfile
├── README.md
└── app files
```

## 🏗️ Build Docker Image

```bash
docker build -t docker-testapp .
```

## 🐳 Run Docker Container

```bash
docker run -d -p 8080:8080 --name testapp docker-testapp
```

## 🔍 Check Running Containers

```bash
docker ps
```

## 📜 View Container Logs

```bash
docker logs testapp
```

## 🛑 Stop Container

```bash
docker stop testapp
```

## ❌ Remove Container

```bash
docker rm testapp
```

## ❌ Remove Docker Image

```bash
docker rmi docker-testapp
```

## 🔄 Docker Workflow

```text
Source Code
     │
     ▼
Docker Build
     │
     ▼
Docker Image
     │
     ▼
Docker Container
     │
     ▼
Running Application
```

## ✨ Features

* Dockerized application
* Easy deployment
* Lightweight image
* Beginner-friendly project
* Simple container management

## 📄 License

MIT License

⭐ If you found this project useful, give it a star!
