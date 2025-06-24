# cicd-demo-gha
# 🚀 CI/CD Pipeline with GitHub Actions, Docker & Render

This project demonstrates a complete CI/CD pipeline for a Python Flask web app using:

- 🧪 **GitHub Actions** for Continuous Integration
- 🐳 **Docker** for containerization
- 🌐 **Render** for Continuous Deployment (free-tier cloud)
- 🔐 **GitHub Secrets** for secure credentials

---

## 🔧 Tech Stack

- Python 3.9 (Flask)
- Docker
- GitHub Actions
- Render.com (Deployment target)
- GitHub Secrets (for CI/CD security)

---

## 📦 Project Structure

```bash
.
├── app/
│   └── main.py             # Flask application
├── Dockerfile              # Build Docker image
├── .github/
│   └── workflows/
│       └── ci-cd.yml       # GitHub Actions workflow
└── README.md               # This file
