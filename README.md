# Dockerized FastAPI Continuous Delivery

This repository demonstrates Continuous Delivery by automating the creation and deployment of a Dockerized FastAPI application using GitHub Actions.

## Files Overview
- **main.py:** FastAPI server that returns JSON data.
- **requirements.txt:** Python dependencies.
- **Dockerfile:** Instructions to build the Docker image.
- **.github/workflows/DockerBuild.yml:** GitHub Actions workflow to build and push the Docker image.

## How to Run Locally
1. **Install Python** and the necessary packages:
   ```bash
   pip install -r requirements.txt
