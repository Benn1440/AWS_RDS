# AWS RDS

Amazon Relational Database Service (Amazon RDS) is a collection of managed services that makes it simple to set up, operate, and scale databases in the cloud. Choose from seven popular engines — Amazon Aurora with MySQL compatibility, Amazon Aurora with PostgreSQL compatibility, MySQL, MariaDB, PostgreSQL, Oracle, and SQL Server — and deploy on-premises with Amazon RDS on AWS Outposts.

## Reference: https://aws.amazon.com/rds/

During this hands-on process, I had to configure an MYSQL Database and a replica with a different disk size to achieve high availability with Amazon RDS Multi-AZ deployments.

![AWS RDS](https://github.com/Benn1440/AWS_RDS/assets/67696393/adda8286-16f7-4019-b193-f5e72b424141)

Also there is the need to always set  rules for inbound traffic that can access the Database, and to achieve security in the cloud, it is paramount to always have your database in a private subnet.

![DB Rules](https://github.com/Benn1440/AWS_RDS/assets/67696393/8862599b-3d8b-4437-987f-dd4c5e1ad555)
