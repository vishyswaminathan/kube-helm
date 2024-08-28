CICD FOR CONTAINERS  
===================
ARCHITECTURE DIAGRAM : ![1CICD](https://github.com/user-attachments/assets/46d84d26-2556-43ff-a9af-e8826ff94ac8)


Description : 
In this project, I've created an CI/CD automation pipeline for software deployment. Code changes made to an application by the developer gets uploaded to a version control system ,GIT hub in this case, which triggers a Jenkins automation pipeline.

Tools: 
GIT - Version control system
Kubernetes - container orchestration tool
Docker - container service
Jenkins - CI/CD
HELM - packaging  and deploying on kubernetes
GIT - Version control system
MAVEN - build tool
SONARCUBE - Code analysis server

Stages: 

1. Fetch Code (includes docker file)
2. Code Test
3. Code analysis using CHECKSTYLE
4. Upload results to Sonarqube server
5. Build Image using MAVEN
6. Docker image pushed to Docker HUB.
7. HELM charts deployed to  Kubernetes Cluster


**************************************************************
**************************************************************

## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
## Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql
