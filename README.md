# AWS-CLF-01
AWS Certified Cloud Practitioner notes

## CLF-C01

* [AWS Certified Cloud Practitioner in 3 steps](https://towardsdatascience.com/3-steps-to-get-aws-cloud-practitioner-certified-in-2-weeks-or-less-772178f48249)

* [AWS Certified Cloud Practitioner resources](https://github.com/yurynino/learning-aws-practitioner)

* [CLF-C01 Schedule and Exam](https://aws.amazon.com/es/certification/certified-cloud-practitioner/?ch=cta&cta=header&p=2)

* [CLF-C01 Skill Builder](https://explore.skillbuilder.aws/learn/course/134/AWS%2520Cloud%2520Practitioner%2520Essentials)

## The Cloud

On-demand resources and applications through the Internet pay-as-you-go.

### Benefits

1. Trade upfront expenses to variable expenses instead.
2. Stop spending money in data centers.
3. Stop guessing capacity.
4. Benefit from massive economies: aggregated use from many customers gives us lower pay-as-you-go.
5. Speed in deploying apps.
6. Go global in minutes.

### Models of service

1. IaaS: net+computers+storage.
2. Paas: hardware and software managed by your provider.
3. Saas: complete solution.

## EC2

Virtual machines.

### Instance types

1. General purpose
2. Compute optimized
3. Memory optimized
4. Accelerated computing
5. Storage optimized

### Pricing

1. On-Demand
2. Savings Plans
3. Reserved Instances
4. Spot Instances
5. Dedicated Hosts

## Cost Management

* AWS Application Cost Profiler

  * [AWS Application Cost Profiler](https://docs.aws.amazon.com/application-cost-profiler/latest/userguide/introduction.html) - Separate costs by tenants

* AWS Billing Conductor

  * [AWS Billing Conductor](https://docs.aws.amazon.com/billingconductor/latest/userguide/what-is-billingconductor.html) - Model the billing relationship with customers or business units

  * [Billing and Cost Management Console](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/billing-what-is.html)

* AWS Budgets

  * [AWS Budgets](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-managing-costs.html) - Managing your costs

* AWS Cost Explorer

  * [AWS Cost Explorer](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-what-is.html) - Analyzing your costs

* AWS Marketplace Subscriptions

  * [AWS Marketplace subscriptions to AWS Service Catalog](https://docs.aws.amazon.com/marketplace/latest/buyerguide/service-catalog.html)

* [Reservation models for other services](https://docs.aws.amazon.com/whitepapers/latest/cost-optimization-reservation-models/reservation-models-for-other-aws-services.html)

* [TCO Pricing Tools](https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/aws-pricingtco-tools.html)

## Business Applications

* Amazon Connect

  * [Amazon Connect](https://docs.aws.amazon.com/connect/latest/adminguide/what-is-amazon-connect.html) - Customers communication and support

* Amazon Simple Email Service

  * [Amazon SES](https://docs.aws.amazon.com/ses/latest/dg/Welcome.html) - Send and receive emails using our own addresses and domains

## Compute

* App Runner

  * [AWS App Runner](https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html) - Deploy from code a container image

* Batch

  * [AWS Batch](https://docs.aws.amazon.com/batch/latest/userguide/what-is-batch.html) - Run workloads

* EC2

  * [Amazon EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html) - Scalable computing - virtual servers

  * [EC2 Auto Scaling](https://aws.amazon.com/es/ec2/autoscaling/)

  * [EC2 Instance purchasing options](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-purchasing-options.html)

  * [EC2 Reserved Instances](https://docs.aws.amazon.com/whitepapers/latest/cost-optimization-reservation-models/amazon-ec2-reserved-instances.html)

* EC2 Image Builder

  * [AWS EC2 Image Builder](https://docs.aws.amazon.com/imagebuilder/latest/userguide/what-is-image-builder.html) - Automate server images management

* Elastic Beanstalk

  * [AWS Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html) - Automate applications deployment by handling capacity, load balancing, scaling and health monitoring

  * [Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) - Applications Container

* Lambda

  * [AWS Lambda](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html) - Run code without managing servers

  * [Working with Go](https://docs.aws.amazon.com/lambda/latest/dg/lambda-golang.html)

  * [Working with Python](https://docs.aws.amazon.com/lambda/latest/dg/lambda-python.html)

* Lightsail

  * [Amazon Lightsail](https://lightsail.aws.amazon.com/ls/docs/en_us/articles/what-is-amazon-lightsail) - Images ready to build websites or web applications

  * [Lightsail Easy Cloud Server](https://aws.amazon.com/es/free/compute/lightsail/?trk=1a1beef8-3d2e-4d52-881c-47f0947193e8&sc_channel=ps&sc_campaign=acquisition&sc_medium=ACQ-P|PS-GO|Brand|Desktop|SU|Compute|Lightsail|ES|ES|Text&s_kwcid=AL!4422!3!588732065412!e!!g!!amazon%20web%20services%20lightsail&ef_id=CjwKCAjw4ayUBhA4EiwATWyBrrfG1zNtv7GcHmJo9kK8OT5XGW0pYAGgvlYSIbdI1L6OhfsKudr-jhoC_jgQAvD_BwE:G:s&s_kwcid=AL!4422!3!588732065412!e!!g!!amazon%20web%20services%20lightsail)

* Outposts

  * [AWS Outposts](https://docs.aws.amazon.com/outposts/latest/userguide/what-is-outposts.html) - Extend AWS to customer premises local private cloud

* Serverless Application Repository

  * [AWS Serverless Application Repository](https://docs.aws.amazon.com/serverlessrepo/latest/devguide/what-is-serverlessrepo.html) - Make it easy to find, deploy and publish serverless applications

  * [Serverless](https://aws.amazon.com/serverless/) - Execute code when necessary

## Containers

* Elastic Container Registry

  * [Amazon ECR](https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html) - Container images repositories

* Elastic Container Service

  * [Amazon ECS](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html) - Container management on a cluster

  * [Amazon ECS on AWS Fargate](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html) - Automate server type election and when to scale or optimize our clusters

* Elastic Kubernetes Service

  * [Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html) - Managed Kubernetes control plane for each cluster

* Red Hat OpenShift Service on AWS

  * [ROSA](https://docs.aws.amazon.com/ROSA/latest/userguide/what-is-rosa.html) - Managed OpenShift for containerized applications

## Data Analytics

* Athena

  * [Amazon Athena](https://docs.aws.amazon.com/athena/latest/ug/what-is.html) - Query service to analyze data in S3

  * [Creating databases and tables](https://docs.aws.amazon.com/athena/latest/ug/work-with-data.html)

  * [Running queries](https://docs.aws.amazon.com/athena/latest/ug/querying-athena-tables.html)

  * [SQL reference](https://docs.aws.amazon.com/athena/latest/ug/ddl-sql-reference.html)

  * [Using workgroups to control query access and costs](https://docs.aws.amazon.com/athena/latest/ug/manage-queries-control-costs-with-workgroups.html)

* Config

  * [AWS Config](https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html) - View of the configurations of AWS resources

  * [AWS Config Rules](https://docs.aws.amazon.com/config/latest/developerguide/evaluate-config.html)

  * [AWS Config vs. CloudTrail](https://www.sumologic.com/blog/aws-config-vs-cloudtrail/)

  * [Using AWS Config](https://docs.aws.amazon.com/config/latest/developerguide/aws-config-landing-page.html)

* Managed Apache Airflow

  * [Amazon MWAA](https://docs.aws.amazon.com/mwaa/latest/userguide/what-is-mwaa.html) - Managed orchestration service for Airflow to setup and operate end-to-end data pipelines

  * [Environemnts](https://docs.aws.amazon.com/mwaa/latest/userguide/using-mwaa.html)

  * [Working with DAG](https://docs.aws.amazon.com/mwaa/latest/userguide/working-dags.html)

* Kinesis

  * [Amazon Kinesis Data Streams](https://docs.aws.amazon.com/streams/latest/dev/introduction.html) - Collect and process large stream of data in real time

  * [Creation and management of streams](https://docs.aws.amazon.com/streams/latest/dev/working-with-streams.html)

* EMR

  * [Amazon EMR](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-what-is-emr.html) - Cluster for big data frameworks Hadoop and Spark

## Database

* Amazon DocumentDB

  * [Amazon DocumentDB](https://docs.aws.amazon.com/documentdb/latest/developerguide/what-is.html) - MongoDB to store data in flexible JSON-like documents

* Amazon Keyspaces

  * [Amazon Keyspaces](https://docs.aws.amazon.com/keyspaces/latest/devguide/what-is-keyspaces.html) - Apache Cassandra NoSQL distributed database

* Amazon MemoryDB for Redis

  * [AWS MemoryDB for Redis](https://docs.aws.amazon.com/memorydb/latest/devguide/what-is-memorydb-for-redis.html) - Durable in-memory database that delivers ultra-fast performance

* Amazon Quantum Ledger Database

  * [Amazon QLDB](https://docs.aws.amazon.com/qldb/latest/developerguide/what-is.html) - Ledger database to track all application data

* Amazon Timestream

  * [Amazon Timestream](https://docs.aws.amazon.com/timestream/latest/developerguide/what-is-timestream.html) - Time series database

* DynamoDB

  * [Amazon DynamoDB](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html) - Fast NoSQL database based on tables of items with attributes

  * [DAX DynamoDB Accelerator](https://aws.amazon.com/es/dynamodb/dax/)

  * [DynamoDB Auto Scaling](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/AutoScaling.html)

* ElastiCache

  * [Amazon ElastiCache](https://docs.aws.amazon.com/elasticache/index.html) - In-memory cache for high performance

  * [Comparing Memcached and Redis](https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/SelectEngine.html)

* Neptune

  * [Amazon Neptune](https://docs.aws.amazon.com/neptune/latest/userguide/intro.html) - Graph database for highly connected datasets

* Relational Database Service

  * [Amazon RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html) - DB instances based on SQL Server, Oracle, MySQL, MariaDB and PostgreSQL

  * [Microsoft SQL Server on Amazon RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_SQLServer.html)

  * [MySQL on Amazon RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_MySQL.html)

  * [PostgreSQL on Amazon RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_PostgreSQL.html)

## Global Infrastructure and Reliability

* [Global Infrastructure](https://aws.amazon.com/about-aws/global-infrastructure/)

## Migration

* Database Migration Service

  * [DMS - Migrate databases uninterruptedly](https://aws.amazon.com/dms/)

* Snow

  * [AWS Snowball](https://aws.amazon.com/snowball/?nc=sn&loc=4)

  * [AWS Snowball Device Differences](https://docs.aws.amazon.com/snowball/latest/ug/device-differences.html)

  * [AWS Snowball Edge device](https://docs.aws.amazon.com/snowball/latest/developer-guide/whatisedge.html) - Move up to 10 PB of data with compute power

  * [AWS Snowball Edge Device Differences](https://docs.aws.amazon.com/snowball/latest/developer-guide/device-differences.html)

  * [AWS Snowcone](https://aws.amazon.com/snowcone/?nc=sn&loc=3)

  * [AWS Snowcone device](https://docs.aws.amazon.com/snowball/latest/snowcone-guide/snowcone-what-is-snowcone.html) - Move up to 8 TB of data

  * [AWS Snowmobile](https://aws.amazon.com/snowmobile/?nc=sn&loc=5) - Move up to 100 PB of data

## Monitoring

* CloudTrail

  * [AWS CloudTrail](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-user-guide.html) - Audit account by recording as events the actions taken by users, roles or services

  * [Working with CloudTrail log files](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-working-with-log-files.html)

* CloudWatch

  * [Amazon CloudWatch](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html) - Monitor resources and applications in real time

  * [Using Amazon CloudWatch alarms](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/AlarmThatSendsEmail.html)

## Networking & Content Delivery

* API Gateway

  * [AWS API Gateway](https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html) - Manage REST, HTTP and WebSocket APIs

* CloudFront

  * [Amazon CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html) - Speed up distribution of web content through edge locations

  * [Edge locations CDN](https://aws.amazon.com/cloudfront/features/?whats-new-cloudfront.sort-by=item.additionalFields.postDateTime&whats-new-cloudfront.sort-order=desc#Global_Edge_Network)

* Direct Connect

  * [AWS Direct Connect](https://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html) - Link internal network to AWS over fiber-optic cable

* Route 53

  * [Amazon Route 53](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html) - DNS to register domains, route traffic and healthcheck resources

* Virtual Cloud Network

  * [Amazon VPC](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html) - Launch resources into a virtual scalable network

* [VPN](https://aws.amazon.com/es/vpn/)

## Security

* Identity and Access Management

  * [AWS IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html) - Control access to resources

  * [Users](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users.html)

  * [User groups](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_groups.html)

  * [Roles](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.html)

* Inspector

  * [Amazon Inspector](https://docs.aws.amazon.com/inspector/latest/user/what-is-inspector.html) - Vulnerability scanner for workloads on EC2 instances and images in ECR

* Key Management Service

  * [AWS KMS](https://docs.aws.amazon.com/kms/latest/developerguide/overview.html) - Create and control cryptographic keys for data on rest

  * [KMS](https://docs.aws.amazon.com/kms/latest/developerguide/control-access.html) - Authentication and access control

* Secrets Manager

  * [AWS Secrets Manager](https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html) - Replace hardcoded credentials in your code

* Web Application Firewall & Shield

  * [AWS Shield](https://docs.aws.amazon.com/waf/latest/developerguide/shield-chapter.html) - Protection against DDos attacks

  * [AWS WAF](https://docs.aws.amazon.com/waf/latest/developerguide/waf-chapter.html) - Allow, block, count or check HTTP(S) requests to CloudFront, API Gateway, Application Load Balancer or AppSync GraphQL

  * [What are AWS WAF, AWS Shield, and AWS Firewall Manager?](https://docs.aws.amazon.com/waf/latest/developerguide/what-is-aws-waf.html)

* [Shared Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/)

## Storage

* AWS Backup

  * [AWS Backup](https://docs.aws.amazon.com/aws-backup/latest/devguide/whatisbackup.html) - Centralized and automated backups

* AWS Elastic Disaster Recovery

  * [AWS EDR](https://docs.aws.amazon.com/drs/latest/userguide/what-is-drs.html) - Minimizes downtime and data loss with replication and point-in-time recovery

* EFS

  * [Amazon Elastic File System](https://docs.aws.amazon.com/efs/latest/ug/whatisefs.html) - Serverless and elastic file system that can be used from multiple compute instances across multiple Availability Zones in a region

* FSx

  * [Amazon FSx for Windows File Server](https://docs.aws.amazon.com/fsx/latest/WindowsGuide/what-is.html) - Native Windows file system

* Simple Storage Service

  * [Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html) - Unlimited size buckets to store objects to be written once and read several times by a unique URL

  * [Amazon S3 Glacier](https://docs.aws.amazon.com/amazonglacier/latest/dev/introduction.html) - Low-cost S3 storage for archiving and backup objects

  * [Object Storage Classes](https://aws.amazon.com/s3/storage-classes/)

  * [S3 faq](https://aws.amazon.com/s3/faqs/)

* Storage Gateway

  * [Amazon S3 File Gateway](https://docs.aws.amazon.com/filegateway/latest/files3/what-is-file-s3.html) - Connect S3 to an on-premises appliance using NFS and SMB

  * [Marketplace](https://aws.amazon.com/marketplace)

  * [Well-Architected Framework](https://aws.amazon.com/es/architecture/well-architected/?wa-lens-whitepapers.sort-by=item.additionalFields.sortDate&wa-lens-whitepapers.sort-order=desc)
