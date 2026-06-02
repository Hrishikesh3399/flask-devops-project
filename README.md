
A simple Flask-based web application developed to demonstrate core DevOps concepts including GitHub version control, Docker containerization, CI/CD pipeline integration, and deployment automation.

## 📌 Project Overview

This project showcases how a Flask application can be integrated with modern DevOps tools and practices to achieve faster development, automated deployment, and better software delivery.

The application is containerized using Docker and managed through GitHub for source code versioning. It serves as a beginner-friendly DevOps implementation project.

## 🛠️ Technologies Used

- Python
- Flask
- Git & GitHub
- Docker
- Docker Compose
- Jenkins
- Linux

## 📂 Project Structure

```text
flask-devops-project/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
├── Jenkinsfile
├── README.md
└── .gitignore
```

## ⚙️ Features

- Flask Web Application
- Dockerized Environment
- Version Control using GitHub
- CI/CD Pipeline Integration
- Easy Deployment Process
- Lightweight and Beginner Friendly

## 🔧 Prerequisites

Make sure the following tools are installed:

- Python 3.x
- pip
- Git
- Docker
- Docker Compose
- Jenkins (Optional for CI/CD)

## 🚀 Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/Hrishikesh3399/flask-devops-project.git
cd flask-devops-project
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/Mac

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run Flask Application

```bash
python app.py
```

Application will run at:

```text
http://localhost:5000
```

## 🐳 Docker Setup

### Build Docker Image

```bash
docker build -t flask-devops-project .
```

### Run Docker Container

```bash
docker run -d -p 5000:5000 flask-devops-project
```

Access application:

```text
http://localhost:5000
```

## 📦 Docker Compose

Start application using Docker Compose:

```bash
docker-compose up -d
```

Stop application:

```bash
docker-compose down
```

## 🔄 CI/CD Pipeline

This project can be integrated with Jenkins to automate:

- Source Code Checkout
- Dependency Installation
- Build Process
- Docker Image Creation
- Deployment

Pipeline configuration is stored in:

```text
Jenkinsfile
```

## 🌐 GitHub Repository

Repository Link:

👉 https://github.com/Hrishikesh3399/flask-devops-project

## 📈 DevOps Workflow

```text
Developer
   │
   ▼
GitHub Repository
   │
   ▼
Jenkins Pipeline
   │
   ▼
Build & Test
   │
   ▼
Docker Image Creation
   │
   ▼
Deployment
```

## 📚 Learning Objectives

This project helps understand:

- Flask Application Development
- Git and GitHub Workflow
- Docker Containerization
- CI/CD Concepts
- Jenkins Automation
- DevOps Best Practices

## 🔮 Future Enhancements

- Kubernetes Deployment
- AWS Cloud Deployment
- Monitoring using Prometheus & Grafana
- Automated Testing Integration
- Multi-Container Architecture

## 👨‍💻 Author

**Hrishikesh B Nair**

GitHub: https://github.com/Hrishikesh3399

LinkedIn: https://www.linkedin.com/in/hrishikesh-b-nair-120401284/

## 📄 License

This project is created for educational and learning purposes as part of DevOps practice and implementation.
