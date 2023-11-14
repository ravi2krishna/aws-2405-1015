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



