# Netflix Clone Backend: CI/CD Deployment on AWS

Spring Boot movie API connected to MongoDB Atlas, containerized with Docker and deployed to AWS EC2.

## What I built
- GitHub Actions pipeline that builds a Docker image and pushes it to Amazon ECR on every push to main
- Dedicated IAM user for the pipeline, with credentials stored as GitHub secrets
- MongoDB Atlas cluster on AWS, with the connection string supplied at runtime, not stored in code
- Deployment on EC2 with Docker Compose and Portainer
- Diagnosed and fixed a container port mismatch

## Stack
Java, Spring Boot, MongoDB Atlas, Docker, GitHub Actions, Amazon ECR, AWS EC2, AWS IAM, Portainer

## Status
Completed and decommissioned to control cloud costs.

## Author
Emmanuel Ibegbu, Cloud Security and DevOps Engineer
