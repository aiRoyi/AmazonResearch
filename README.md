# AmazonResearch

## Compute:

* Amazon Elastic Compute Cloud (EC2)
** Start with EC2
1. Create an instance(Amazon Linux 2 AMI) on AWS web and running it, save a keypair.pem file.
2. In puttygen, load keypair.pem file and click button "Save private key" generate and save a ppk file to local.
3. Open putty, input IP which is in the EC2 Description dashboard, and import the ppk file(Connection - SSH - Auth)
4. Click "Open"

* Elastic Load Balancing & Auto Scaling 

* Amazon ECS: Amazon ECS service allows you to run Docker-enabled applications packaged as containers across a cluster of EC2 instances without requiring you to manage a complex and administratively heavy cluster management system

* AWS Elastic Beanstalk: AWS Elastic Beanstalk service helps to install, distribute and deploy web applications

* AWS Lambda: AWS Lambda lets your run your own code in response to events in a scalable and highly available serverless environment

* AWS Batch: AWS Batch is used to manage and run batch computing workloads within AWS

* Amazon Lightsail: Amazon Lightsail service is essentially a Virtual Private Server (VPS) backed by AWS infrastructure
