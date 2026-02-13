# Jenkins Automation Lab

## Project Workflow & Proof of Concept

### 1. Docker Setup
Jenkins is running inside a Docker container, mapped to port 8080.
![Docker Setup](1. Docker Environment Setup.png)

### 2. Automation Script (`script.sh`)
This script handles the creation of the deployment folder structure.
![Script](2. Automation Script Logic (script.sh).png)nfiguration (Jenkinsfile).png


### 3. Pipeline Configuration (`Jenkinsfile`)
Defined as "Pipeline as Code," telling Jenkins how to execute the build.
![Pipeline Configuration](3. Pipeline Configuration (Jenkinsfile).png)

### 4. GitHub Webhook via ngrok
Configuring the tunnel to allow GitHub to talk to our local Jenkins server.
![Webhook](4. GitHub Webhook Integration.png)

### 5. Successful Webhook Trigger
Verification that Build #4 was automatically started by a GitHub push.
![Build Trigger](5. Automated Build Trigger.png)

### 6. Pipeline Stage View
Visual representation of the successful stages of the automation.
![Pipeline Stages](6. Pipeline Stage Visualization.png)

### 7. Console Output
Final logs confirming the project structure was created and the build finished with SUCCESS.
![Console Output](7. Console Output & Final Verification.png)# Automated-CI