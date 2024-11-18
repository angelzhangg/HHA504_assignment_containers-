## Objective
The objective of this assignment is to provide you with hands-on experience in deploying and managing containers using either GCP Cloud Run and Azure Container Apps. You will learn how to containerize an application with Docker and deploy it on both platforms.

## Instructions

### 1. Containerize a Simple Application
- **Create a Docker Image:**
  - Choose a simple application (e.g., a Python Flask app) and create a Dockerfile to containerize the application.
    - You can use the Flask app from module10 as a starting point.
    - Please update it or customize it to make it your own. Try to spend about 30 minutes doing updates to the app. Some ideas:
      - Add a new route that returns a different message, or random number
      - Insert some HTML into the return message, etc...
  - Build the Docker image locally and test it to ensure that it runs as expected.

### 2. Deploy to GCP Cloud Run
- **GCP Cloud Run:**
  - Push your Docker image to DockerHub
  - Deploy the containerized application to GCP Cloud Run.
  - Configure the deployment, including setting environment variables and scaling options.
  - Test the deployed application to ensure it is running correctly.

### 3. Deploy to Azure Container Apps (OPTIONAL)
- **Azure Container Apps:**
  - Push your Docker image to DockerHub.
  - Deploy the containerized application to Azure Container Apps.
  - Configure the deployment similarly to the GCP deployment, including environment variables and scaling options.
  - Test the deployed application to ensure it is running as expected.
