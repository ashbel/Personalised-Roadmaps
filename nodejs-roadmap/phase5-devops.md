# Phase 5 – DevOps & Deployment
## Goals
- Containerize Node.js applications using Docker and Docker Compose.
- Set up CI/CD pipelines with GitHub Actions for build, test and deployment.
- Understand basic Kubernetes concepts (pods, deployments, services) for scaling.
- Deploy your applications to a cloud platform (e.g. Heroku, AWS, DigitalOcean) and manage environment variables and secrets.
- Implement monitoring and logging.

## Topics & Resources
- **Docker**: Creating Dockerfiles for Node.js + NestJS services; multi-stage builds for production.
- **Docker Compose**: Orchestrating multi-service stacks locally (API, DB, message broker).
- **CI/CD with GitHub Actions**: Building and testing Node.js apps, running linting and tests, publishing Docker images.
- **Kubernetes Basics**: Pods, deployments, services, ConfigMaps and Secrets; optional tools like k3d or Minikube.
- **Deployment Platforms**: Compare options like Heroku, Render, Fly.io, AWS Elastic Beanstalk, and choose one to deploy your project.
- **Environment & Secrets Management**: Use dotenv, GitHub secrets, and secret managers.
- **Monitoring & Logging**: Introduce tools like Winston for logging, Prometheus/Grafana or LogRocket for monitoring.

## Practice Tasks
- Write Dockerfiles for your Phase 2 backend and Phase 3 frontend; build and run them locally.
- Create a `docker-compose.yml` to run the backend, frontend and database together.
- Set up a GitHub Actions workflow that lints, tests and builds the Docker images on every push; configure it to push images to a container registry (e.g. Docker Hub or GitHub Container Registry).
- Deploy your application stack to a chosen platform (start with Heroku or Render for simplicity). Document the deployment steps.
- Optionally explore running your services on a local Kubernetes cluster (e.g. Minikube) and deploy using manifests or Helm charts.
- Set up environment variables and secrets for different environments (development, staging, production).
- Add basic logging and monitoring to your services.

## Deliverables
- A `phase5-devops` subfolder containing Dockerfiles and docker-compose file for your services.
- A GitHub Actions workflow YAML file for CI/CD.
- Deployment scripts or notes describing how to deploy your services to the chosen platform.
- Optional Kubernetes manifests or Helm charts if you explored Kubernetes.
- Documentation summarizing environment configuration, secrets management and monitoring setup.
