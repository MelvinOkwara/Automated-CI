# Jenkins Automation Lab

## Project Workflow & Proof of Concept

### 1. Docker Setup
Jenkins is running inside a Docker container, mapped to port 8080.
![Docker Setup](screenshots/1-docker-setup.png)

### 2. Automation Script (`script.sh`)
This script handles the creation of the deployment folder structure.
![Script](screenshots/2-script-sh.png)

### 3. Pipeline Configuration (`Jenkinsfile`)
Defined as "Pipeline as Code," telling Jenkins how to execute the build.
![Jenkinsfile](screenshots/3-jenkinsfile.png)

### 4. GitHub Webhook via ngrok
Configuring the tunnel to allow GitHub to talk to our local Jenkins server.
![Webhook](screenshots/4-github-webhook.png)

### 5. Successful Webhook Trigger
Verification that Build #4 was automatically started by a GitHub push.
![Build Trigger](screenshots/5-build-trigger.png)

### 6. Pipeline Stage View
Visual representation of the successful stages of the automation.
![Pipeline Stages](screenshots/6-pipeline-stages.png)

### 7. Console Output
Final logs confirming the project structure was created and the build finished with SUCCESS.
![Console Output](screenshots/7-console-output.png)# Automated-CI