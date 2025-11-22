# Jenkins First Job – CI/CD Automation Project

This repository demonstrates how I created and executed my **first complete CI/CD pipeline** using **Jenkins + GitHub + Maven**.  
It shows how source code is automatically pulled from GitHub, built using Maven, and monitored through the Jenkins dashboard.

![Jenkins Dashboard]()

---

## 🚀 Project Overview
This project is a practical hands-on implementation of Continuous Integration using Jenkins.  
The goal of this repo is to showcase how a simple Java/Maven project can be:

- Cloned from GitHub  
- Built automatically through Jenkins  
- Packaged using Maven  
- Triggered on-demand or through webhooks  
- Successfully executed with logs, status, and artifacts  

This is part of my DevOps learning journey to master CI/CD, automation, pipelines, and build systems.

---

## 🔧 Tools & Technologies Used

- **Jenkins** – CI/CD automation server  
- **GitHub** – Code repository  
- **Maven** – Build & dependency management  
- **Java / Spring Boot** – Application source  
- **Windows Environment** – Jenkins setup  
- **Jenkins Plugins** – Git plugin, Maven integration, workspace cleanup  

---

## 📂 Project Structure

Jenkins-first-Job/
│
├── src/ # Java source code
├── pom.xml # Maven build configuration
├── mvnw / mvnw.cmd # Maven wrapper scripts
├── Jenkins Dashboard/ # (optional) screenshots
└── README.md


---

## ✔️ What I Did in This Project

- Created a **Freestyle Jenkins job**  
- Connected GitHub repository using credentials  
- Configured Jenkins to automatically clone the repo  
- Added Maven build step using:  

## mvn clean package -DskipTests

- Fixed multiple build issues (Maven errors, POM issues, test failures)  
- Successfully packaged the application using Maven  
- Verified build logs, artifacts, and console output  
- Added dashboard screenshot to track the completed build  

---

## 📦 How to Run the Project Locally

1. Clone the repository  
 ```bash
 git clone https://github.com/harshakanduri/Jenkins-first-Job.git
 cd Jenkins-first-Job

2. Build the project

./mvnw clean package

(Use mvnw.cmd on Windows)

3. Run the application:

java -jar target/*.jar

## Jenkins Build Configuration

Inside Jenkins:

## Source Code Management → Git

* Repository URL:

https://github.com/harshakanduri/Jenkins-first-Job.git


* Branch: main

Build → Invoke top-level Maven targets

* Goals:

clean package -DskipTests


After setup, clicking Build Now will automatically run the CI pipeline.

## 🌟 What I Learned

* How CI/CD works in real time

* How to configure Jenkins jobs from scratch

* How Maven builds work inside Jenkins

* How to troubleshoot build failures

* How GitHub → Jenkins integration works

* How DevOps tools connect together to automate builds

This project was a big confidence boost in my DevOps journey!






