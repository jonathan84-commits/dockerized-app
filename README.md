# Dockerized Flask Application

## 📌 Overview
This project demonstrates how to containerize a simple Python Flask application using Docker and Docker Compose to ensure consistent behavior across different environments.

It solves the common problem of applications working on one machine but failing on another.

---

## ❓ Problem
Developers often face environment inconsistencies:
- Different OS versions
- Missing dependencies
- Conflicting configurations

This leads to the classic issue:
> “It works on my machine.”

---

## ✅ Solution
Using Docker and Docker Compose, the application and its dependencies are packaged into a container that runs identically on any system with Docker installed.

---

## 🛠 Technologies Used
- Python (Flask)
- Docker
- Docker Compose
- Linux

---

## 🚀 How to Run the Project

### Prerequisites
- Docker
- Docker Compose

### Steps
```bash
git clone <your-repo-url>
cd dockerized-app
docker compose up --build

