## Cloud-Native DevSecOps Pipeline: Secure Flask Web Application on AWS 🚀

### Overview 📌
This project demonstrates a cloud-native DevSecOps pipeline for deploying a secure Flask-based web application using Docker and AWS <br>
The goal of this project is to implement a fully automated CI/CD pipeline with integrated security checks, ensuring that applications are built, scanned, and deployed securely in a production-like environment

### Architecture 🏗️
![Diagram](./asset/Diagrame.jpg)

### Tech Stack 🛠️
- Application : Flask (Web Framework)
- Containerization : Docker
- CI/CD : Jenkins
- Security Tools : SonarQube (Code Quality Analysis) | Trivy (Container Vulnerability Scanning)
- Cloud Services (AWS) : ECR (Elastic Container Registry) | EC2 (Compute Instance) | IAM (Access Control & Security)

### CI/CD Pipeline Flow ⚙️
![flow](./asset/flow.gif)

### Security Implementation 🔐
- Integrated SonarQube for static code analysis
- Used Trivy to detect vulnerabilities in Docker images
- Applied IAM roles to enforce secure access control
- Followed DevSecOps “Shift-Left” principle

## Setup Instructions 🚀
### Prerequisites
- Docker installed
- AWS account
- Jenkins configured
- SonarQube server setup

### Steps
```bash
git clone https://github.com/your-username/your-repo.git
```
