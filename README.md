# Jenkins Automation Lab

## Project Workflow & Proof of Concept

### 1. Docker Setup
Jenkins is running inside a Docker container, mapped to port 8080.
![Docker Setup](01-docker-setup.png)

### 2. Automation Script (script.sh)
This script handles the creation of the deployment folder structure.
![Script Logic](02-script-logic.png)

### 3. Pipeline Configuration (Jenkinsfile)
Defined as "Pipeline as Code," telling Jenkins how to execute the build.
![Jenkinsfile](03-jenkinsfile.png)

### 4. GitHub Webhook via ngrok
Configuring the tunnel to allow GitHub to talk to our local Jenkins server.
![Webhook](04-webhook-setup.png)

### 5. Successful Webhook Trigger
Verification that Build was automatically started by a GitHub push.
![Build Trigger](05-build-trigger.png)

### 6. Pipeline Stage View
Visual representation of the successful stages of the automation.
![Pipeline Stages](06-stage-view.png)

### 7. Final Verification
Console output showing the successful execution of the script.
![Verification](07-final-verification.png)