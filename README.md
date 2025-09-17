# 🚀 Simple Node.js App

A minimal **Node.js application** with a sample **GitHub Actions workflow** for CI/CD.  
This project demonstrates building and running the app inside a Docker container.  

---

## 📦 Features
- Simple Node.js app (lightweight, easy to understand).  
- Pre-configured **Dockerfile** for containerized builds.  
- Ready-to-use **GitHub Actions workflow** for automation.  
- Quick local setup with Docker.  

---

## 🛠️ Prerequisites
Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (if you want to run locally without Docker)  
- [Docker](https://www.docker.com/)  
- [Git](https://git-scm.com/)  

---

## 🔨 Build Docker Image
Run the following command to build the Docker image:  

```bash
docker build -t simple-nodejs-app:v0.0.1 .
```

## ▶️ Run Application

Start the app in Docker using:

```bash
docker run -p 90:80 --rm simple-nodejs-app:v0.0.1
```

Then open http://localhost:90 in your browser.

## 🧪 Run Locally (Optional)

If you want to run without Docker:

```bash
npm install
npm start
```

The app will run at http://localhost:3000
 by default (depending on your config).
