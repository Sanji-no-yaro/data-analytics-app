# Data Analytics Application with CI/CD Pipeline

## Project Overview

**Objective:**  
The goal of this project was to build a Python-based data analytics application and set up an automated CI/CD pipeline to handle building, testing, deploying, and monitoring the app.

**Technologies Used:**
- **Version Control:** GitHub
- **Containerization:** Docker
- **Orchestration:** Minikube (Kubernetes)
- **Operating System:** Ubuntu
- **CI/CD Tool:** Jenkins
- **Testing Tools:** Pytest and Selenium (for web interface, if applicable)
- **Configuration Management:** Ansible or Chef
- **Monitoring:** AWS CloudWatch

## What We Did

### 1. Project Setup on GitHub
- Created a GitHub repository to store the project code.
- Set up the project structure and added sample data.

### 2. Application Development
- Built a Python application for data analysis.
- Optionally included a web interface using Flask.
- Added sample data for testing.

### 3. Containerization with Docker
- Used Docker to package the application into a container.
- Built and ran the Docker image to ensure it worked correctly.

### 4. CI/CD Pipeline with Jenkins
- Installed Jenkins to automate building, testing, and deploying the app.
- Created a Jenkinsfile to define the CI/CD pipeline steps.
- Set up Jenkins to connect with GitHub and Docker.

### 5. Testing
- Wrote tests using Pytest to check the app’s functionality.
- Used Selenium for web interface testing (if applicable).

### 6. Deployment with Minikube
- Set up Minikube to run a local Kubernetes cluster.
- Created configuration files to deploy the app to Minikube.
- Deployed the app and verified its functionality.

### 7. Configuration Management
- Used Ansible (or Chef) to automate server setup and deployment.

### 8. Monitoring (Bonus)
- Set up AWS CloudWatch to monitor app performance.
- Created dashboards to visualize key metrics like CPU and memory usage.

## Challenges We Faced

- **Docker Networking Issues:** Encountered problems with Docker networking and port settings, resolved through configuration adjustments.
- **Minikube Setup:** Faced issues with local Kubernetes setup due to resource limits, which were addressed by optimizing settings.
- **Jenkins Integration:** Experienced difficulties connecting Jenkins with GitHub and Docker, requiring troubleshooting.
- **Testing Automation:** Had trouble with Selenium for web UI testing due to browser compatibility, fixed by adjusting settings.

## Key Learnings

- **CI/CD Pipeline Design:** Learned how to set up and manage an automated CI/CD pipeline.
- **Containerization Best Practices:** Gained experience with Docker for creating and managing application containers.
- **Automated Testing:** Improved skills in writing and running automated tests with Pytest and Selenium.
- **Deployment Strategies:** Learned about deploying applications using Minikube and managing configurations with tools like Ansible or Chef.
- **Monitoring:** Acquired knowledge in using AWS CloudWatch for tracking application performance and setting up monitoring dashboards.

## Conclusion

This project successfully built a data analytics application and implemented an automated CI/CD pipeline. We used tools like Docker, Minikube, Jenkins, and others to streamline the development and deployment process. Despite facing some challenges, the project provided valuable insights into modern software practices and toolsets.
