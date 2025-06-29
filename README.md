# weekday-assignment
# Infrastructure Engineer Trainee Assignment 🚀

This assignment demonstrates a simple containerized Flask application deployed to a local Kubernetes cluster using Docker, Minikube, and kubectl. It includes steps to build, deploy, expose, and verify the app.

---

## 📦 Tech Stack Used

- Python + Flask
- Docker
- Kubernetes (Killercoda Playground)
- kubectl
- DockerHub

---

## ✅ Task Overview

### 1. Dockerized Flask App

- `app.py` is a basic Flask app returning **"Hello, World!"** at the `/` route.
- Containerized using a `Dockerfile`
- Image built and pushed to DockerHub:  
  [`tanzeel1705/hello-world-app`](https://hub.docker.com/r/tanzeel1705/hello-world-app)

---

## ⚙️ Setup Instructions

### 🔧 Step 1: Clone Repo
```bash
git clone https://github.com/<your-username>/infra-trainee-assignment.git
cd infra-trainee-assignment
