# R-D-S
Relational Database Service
# Amazon RDS (Relational Database Service)

## What is  Amazon RDS?

Amazon Relational Database Service (Amazon RDS) is a web service that makes it easier to set up, operate, and scale a relational database in the AWS Cloud. It provides cost-efficient, resizable capacity for an industry-standard relational database and manages common database administration tasks.

## What are DB Instances?

A *DB instance* is an isolated database environment in the AWS Cloud. The basic building block of Amazon RDS is the DB instance.

Your DB instance can contain one or more user-created databases. You can access your DB instance by using the same tools and applications that you use with a standalone database instance. You can create and modify a DB instance by using the AWS Command Line Interface (AWS CLI), the Amazon RDS API, or the AWS Management Console.

## DB Engines

A *DB engine* is the specific relational database software that runs on your DB instance. Amazon RDS currently supports the following engines:

- Db2
- MariaDB
- Microsoft SQL Server
- MySQL
- Oracle
- PostgreSQL

## Steps to Create a Database

- Login to AWS Console using your Login Credentials.
- Create one instance.
- Search RDS in the Search box.
- You will be directed to the RDS Dashboard.


- Click on the database in the sidebar.
- Click on the Create database.


- Choose a database creation method.
- There are two creation methods - ***Standard create*** (You set all of the configuration options, including ones for availability, security, backups, and maintenance.)

 - ***Easy Create*** (Use recommended best-practice configurations. Some configuration options can be changed after the database is created.)


- Choose the engine type that you require.


- Choose the engine version.
- Choose a sample template to meet your requirements.


- In Settings, give the database a name.
- Assign a master username for your DB Instance.


- Give a password to the user.


- Configure the Connectivity.



- Click on Create database


- The database is created Successfully.


- Click on the name of the database to view the details.


- Add the database port in the security group.
- And while creating the database choose the security group that is created with the database port.
- Connect the instance.
- Install MariaDB.
- connect to the database and create a database.

```jsx
yum install mariadb105 -y
mariadb --version
mysql -h rdsendpoint -u username -p password
```


## Summary

Following these steps, we can create a database using RDS.
