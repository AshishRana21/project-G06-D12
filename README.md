#  React Education app CI/CD Application

A React Education web site built using **Node.js, HTML, CSS, and JavaScript**, containerized with **Docker**, and automated using **GitHub Actions CI** with a **Jenkins-ready CI/CD architecture**.

This project demonstrates a real-world DevOps workflow from development to deployment.

---

## 🚀 Features

- Static frontend (HTML, CSS, JavaScript)
- Docker & Docker Compose support
- GitHub Actions CI pipeline
- Jenkins-ready CI/CD structure
- Clean and professional project structure

---

## 🧰 Tech Stack

**Frontend:**
- HTML
- CSS
- JavaScript


**Containerization:**
- Docker
- Docker Compose

**CI/CD:**
- GitHub Actions
- Jenkins (ready)

**Version Control:**
- Git
- GitHub

---

## 📁 Project Structure

```bash
nodejs-retail-cicd/
│
├── frontend/                # Frontend UI
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── assets/                  # Static assets
│
├── src/                     # Backend source code
│   └── index.js
│
├── tests/                   # Backend tests
│
├── .github/workflows/
│   └── ci.yml               # GitHub Actions pipeline
│
├── Dockerfile               # Docker build file
├── docker-compose.yml      # Docker Compose config
├── package.json
├── README.md
└── .gitignore
```

---

## 💻 Run Locally (Without Docker)

### Step 1: Install dependencies

```bash
npm install
```

### Step 2: Start server

```bash
npm start
```

### Step 3: Open browser

```
http://localhost:3000
```

---

## 🐳 Run with Docker

### Build Docker Image

```bash
docker build -t education-app .
```

### Run Docker Container

```bash
docker run -p 3000:3000 education-app
```

Open:

```
http://localhost:3000
```

---

## 🐙 Run with Docker Compose (Recommended)

### Start containers

```bash
docker compose up --build
```

### Stop containers

```bash
docker compose down
```

---

## ⚙️ CI/CD Pipeline

This project supports:

✅ GitHub Actions  
✅ Jenkins CI/CD  
✅ Docker container build  
✅ Automated deployment ready  

Pipeline file location:

```
.github/workflows/ci.yml
```

---

## ✅ Jenkins-Ready CI/CD Structure

This project is structured for easy integration with Jenkins:

- Automated builds
- Docker image creation
- Test execution
- Deployment ready

---

## 🌐 Application URL

Local:

```
http://localhost:3000
```

---

## 📦 Future Improvements

- Kubernetes deployment
- Database integration
- Authentication system
- Monitoring with Prometheus & Grafana

---

