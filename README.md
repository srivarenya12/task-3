# My DevSecOps App
![Build](https://github.com/srivarenya12/task-3/actions/workflows/ci.yml/badge.svg)
![CodeQL](https://github.com/srivarenya12/task-3/actions/workflows/codeql-analysis.yml/badge.svg)

DevSecOps Demo App
Overview:
This is a minimal Python Flask web API created to demonstrate DevSecOps practices.
It includes automated CI/CD pipelines with linting, testing, and security scanning.

Features

Simple Flask API (app.py) with a test endpoint.

Unit tests with pytest (test_app.py).

Linting with flake8.

Security scanning with Bandit.

GitHub Actions pipeline (ci.yml) that runs on every push/PR.

Build status badge.

Running locally:
# Create virtual environment
python -m venv venv
.\venv\Scripts\activate   # On Windows
source venv/bin/activate  # On Linux/Mac

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py

App will be available at: http://127.0.0.1:5000/

Security & Quality Gates:

flake8 → Python code style checks.

pytest → Automated unit tests.

bandit → Static application security testing (SAST).

GitHub Actions → Automated CI/CD pipeline for DevSecOps.

CI/CD Pipeline:

Every commit or pull request triggers:

Lint check

Unit tests

Security scan

