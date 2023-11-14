## RDS

- A Relational Database (concept) is a data structure that allows you to link information from different tables.
- Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate and scale a relational database in the cloud.
- It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching and backups.
- It frees you to focus on your applications rather than focusing administrative works

## RDS LAB

- create a database called jwt & add a table called user
- show databases;
- create database jwt;
- show databases;
- use jwt;
- show tables;

```sql
CREATE TABLE `USER` (
  `id` int(10) unsigned NOT NULL auto_increment,
  `first_name` varchar(45) NOT NULL,
  `last_name` varchar(45) NOT NULL,
  `email` varchar(45) NOT NULL,
  `username` varchar(45) NOT NULL,
  `password` varchar(45) NOT NULL,
  `regdate` date NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE = InnoDB DEFAULT CHARSET = latin1;
```
- select * from USER;

## Tomcat

- Tomcat is an application server for running java web applications
- Install Java
- sudo apt install openjdk-11* -y
- Setup Tomcat Software
- wget https://archive.apache.org/dist/tomcat/tomcat-7/v7.0.94/bin/apache-tomcat-7.0.94.tar.gz
- tar xvf apache-tomcat-7.0.94.tar.gz
- cd apache-tomcat-7.0.94/bin
- ./startup.sh
- Browse the tomcat server by public-ip:8080, you will be able to see the Tomcat page


