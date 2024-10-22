Medium artcle Link:

https://medium.com/@parrayhuzaif03/building-my-first-automated-ci-cd-pipeline-with-jenkins-github-sonarqube-docker-and-aws-ecr-0b9e12115f99

Prerequisites
JDK 8 (or Oracle JDK8 as specified in the Jenkinsfile)
Maven 3
MySQL 8
Docker
Jenkins
SonarQube
Technologies
Spring MVC
Spring Security
Spring Data JPA
Maven
JSP
Docker
Jenkins
SonarQube
MySQL
AWS ECS & ECR
Database
In this project, we are using MySQL as the database.

SQL dump file:

Located at /src/main/resources/db_backup.sql.
The db_backup.sql file is a MySQL dump file, and we need to import it to the MySQL database server using the following command:
bash
mysql -u <user_name> -p accounts < db_backup.sql
