# Flask CI/CD App 🚀

This is a simple Flask web app to demonstrate CI/CD using GitHub Actions and deployment to AWS via Terraform.

## How to Run Locally

```bash
docker build -t flask-cicd-app .
docker run -p 5000:5000 flask-cicd-app
