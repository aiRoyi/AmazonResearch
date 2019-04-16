# AmazonResearch

## Compute

* Amazon Elastic Compute Cloud (EC2)

* Elastic Load Balancing & Auto Scaling 

* Amazon ECS: Amazon ECS service allows you to run Docker-enabled applications packaged as containers across a cluster of EC2 instances without requiring you to manage a complex and administratively heavy cluster management system

* AWS Elastic Beanstalk: AWS Elastic Beanstalk service helps to install, distribute and deploy web applications

* AWS Lambda: AWS Lambda lets your run your own code in response to events in a scalable and highly available serverless environment

* AWS Batch: AWS Batch is used to manage and run batch computing workloads within AWS

* Amazon Lightsail: Amazon Lightsail service is essentially a Virtual Private Server (VPS) backed by AWS infrastructure

### Start with EC2

1. Create an instance(Amazon Linux 2 AMI) on AWS web and running it, save a keypair.pem file.
2. In puttygen, load keypair.pem file and click button "Save private key" generate and save a ppk file to local.
3. Open putty, input IP which is in the EC2 Description dashboard, and import the ppk file(Connection - SSH - Auth)
4. Click "Open"

## Storage

* Amazon Simple Storage Service (S3): S3 provides secure, durable, and highly scalable object storage

* Amazon Glacier

* EC2 Instance Store Volumes

* Elastic Block Store (EBS): EBS offers persistent and durable data storage than EC2 Instance Store Volumes

* Elastic File System (EFS)

* Amazon CloudFront: Amazon CloudFront is a content delivery network(CDN)

* AWS Storage Gateway: Storage Gateway is a software appliance offers File, Volume and Tap Gateway configurations

* AWS Snowball

### Create S3 Bucket

1. Create Bucket with unique bucket name and choosen region
2. Click into Bucket created, Click "+ Create Folder", you can choose encryption for the object, then click "Save"
3. Click on the folder just created, Click the "Upload" button
4. Click "Add Files". Browse to and select the local file you want to upload or drag and drop the logo file onto the wizard
5. Click "Next", you can set permissions and set properties, you can add Metadata for the file. Click "Upload" to upload the file
6. If you want to get the file from link, click "Actions" -> "Make public"

