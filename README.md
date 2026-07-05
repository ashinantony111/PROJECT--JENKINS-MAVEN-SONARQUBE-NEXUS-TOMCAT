#  End-to-End CI/CD Pipeline for a Java Web Application
This project demonstrates the implementation of a complete CI/CD pipeline for a Java Maven web application using modern DevOps tools on AWS EC2.

##  Project Overview

The pipeline automates the entire software delivery process, including:
- Source Code Management using GitHub
- Continuous Integration with Jenkins
- Build Automation using Maven
- Code Quality Analysis with SonarQube
- Artifact Management with Nexus Repository
- Automated Deployment to Apache Tomcat
- Hosting on AWS EC2 (Ubuntu)

## 🛠️ Tools & Technologies

- GitHub
- Maven
- SonarQube
- Nexus Repository Manager
- Apache Tomcat
- AWS EC2 (Ubuntu)
- Java
- Maven WAR Project


## ⚙️ CI/CD Pipeline Flow
1. Developer pushes code to GitHub.
2. Jenkins clones the repository.
3. Maven builds the application and generates a WAR file.
4. SonarQube performs code quality analysis.
5. WAR artifact is uploaded to Nexus Repository.
6. Jenkins deploys the WAR file to Apache Tomcat using SCP over SSH.
7. The application is successfully deployed on the Tomcat server.


## 📂 Project Structure

```
src/
Jenkinsfile
pom.xml
README.md
architecture/
screenshots/
```

---

## 🏗️ Architecture

https://github.com/ashinantony111/PROJECT--JENKINS-MAVEN-SONARQUBE-NEXUS-TOMCAT/tree/3e27dc8aa7403bc064d651cb794afb3fe20d93cd/architeture
---

## 📸 Project Screenshots

### Jenkins Pipeline
![Pipeline](screenshots/06-pipeline-success.png)

### SonarQube Analysis
![SonarQube](screenshots/03-sonarqube-analysis.png)

### Nexus Repository Upload
![Nexus](screenshots/04-nexus-upload.png)

### Apache Tomcat Deployment
![Tomcat](screenshots/05-tomcat-deployment.png)

---

## ✅ Features

- Automated CI/CD Pipeline
- Continuous Code Quality Analysis
- Artifact Version Management
- Automated Deployment
- End-to-End DevOps Workflow
- AWS EC2 Based Infrastructure

---

## 👨‍💻 Author

Ashin Antony

LinkedIn: www.linkedin.com/in/ashin-antony-7186b3389

GitHub: https://github.com/ashinantony111

