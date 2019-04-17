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

* Amazon CloudFront: Amazon CloudFront is a content delivery network(CDN)(https://aws.amazon.com/cloudfront/)

* AWS Storage Gateway: Storage Gateway is a software appliance offers File, Volume and Tap Gateway configurations(https://docs.aws.amazon.com/storagegateway/latest/userguide/StorageGatewayConcepts.html)

    * File gateways
    * Cached volume gateways
    
        *Both file gateways and cached volume gateways provide local caches to store frequently accessed data.*
    
    * Stored valume gateways: Stored volume gateways keep all files locally, so all stored data can be retrieve with reduced latency
    * Tape gateways

* AWS Snowball(https://docs.aws.amazon.com/snowball/latest/ug/whatissnowball.html)

### Create S3 Bucket

1. Create Bucket with unique bucket name and choosen region
2. Click into Bucket created, Click "+ Create Folder", you can choose encryption for the object, then click "Save"
3. Click on the folder just created, Click the "Upload" button
4. Click "Add Files". Browse to and select the local file you want to upload or drag and drop the logo file onto the wizard
5. Click "Next", you can set permissions and set properties, you can add Metadata for the file. Click "Upload" to upload the file
6. If you want to get the file from link, click "Actions" -> "Make public"

### Manage the storage space of EC2 instance using Amazon EBS

1. In EC2 instance Overview, select ELASTIC BLOCK STORE -> Volumes
2. Click "Create Volume", Set the Volume Type, Size, Availability Zone and etc...

    *Note: If you don't create the volume in the same availability zone used by the EC2 instance where it should be used, you will not be   able to attach it! That is why you need to know the Availability Zone before creating a new volume.*

3. After created, you can see the volume state is available in the checkbox.  Right-clicking on it and selecting the Attach Volume action
