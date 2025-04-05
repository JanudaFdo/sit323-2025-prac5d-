# sit323-2025-prac5d

# SIT323 Practical 5.1P - Docker Deployment

## Overview
Deployed a Node.js application to Google Artifact Registry using Docker.

1. Build Docker image:
docker build -t my-app .

2. Tag for Artifact Registry:
docker tag my-app australia-southeast1-docker.pkg.dev/sit323-25t1-andibuduge-a31fff2/task2df/my-app:latest

3. Push to registry:
docker push australia-southeast1-docker.pkg.dev/sit323-25t1-andibuduge-a31fff2/task2df/my-app:latest
