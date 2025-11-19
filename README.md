# Hello CICD App

A simple Python Flask application demonstrating DevSecOps pipeline with GitHub Actions and Kubernetes.

## Project Structure
- `app/` - Python application code
- `k8s/` - Kubernetes manifests
- `.github/workflows/` - GitHub Actions workflows
- `docs/` - Project documentation

## Quick Start
```bash
# Local development
pip install -r requirements.txt
python app/app.py

# Docker
docker build -t hello-app .
docker run -p 5000:5000 hello-app