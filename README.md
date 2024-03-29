# Prerequisites
- JDK 11
- Maven 3
- MySQL 8 

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
- AWS ECR / EC2 / VPC / SonarQube Analysis   
# Database
I used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu
- $ sudo apt-get update
- $ sudo apt-get install mysql-server or mysql-client 

Then look for the file :
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file. Import db_backup.sql file into mysql server
- > mysql -u <user_name> -p accounts < db_backup.sql

Link to full project -> 
