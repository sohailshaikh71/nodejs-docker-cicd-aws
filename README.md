# Node.js Docker CI/CD on AWS EC2

Containerized a Node.js app using Docker and automated the deployment to AWS EC2 using GitHub Actions CI/CD pipeline.

## Tools & Technologies
- Node.js
- Docker
- GitHub Actions
- AWS EC2

## How It Works
1. Developer pushes code to main branch
2. GitHub Actions workflow triggers automatically
3. Docker image is built
4. App is deployed to AWS EC2 via SSH

## Project Structure
├── index.js
├── package.json
├── Dockerfile
└── .github/
└── workflows/
└── deploy.yml

## Key Concepts Demonstrated
- Dockerizing a Node.js application
- Writing a CI/CD pipeline using GitHub Actions
- Automated deployment to AWS EC2
- Managing secrets securely in GitHub
