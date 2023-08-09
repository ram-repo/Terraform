# AWS
**Compute:**  

**Provision EC2 Instances:**

Task\_1: Create EC2 instances in a specific subnet using Terraform.

Details: Define instance type, AMI, subnet, security group, and key pair for the EC2 instances.

**Implement Auto Scaling Group:**

Task\_2: Set up an Auto Scaling Group with desired capacity, scaling policies, and cooldown periods.

Details: Define launch configuration, scaling policies based on metrics, and instance health checks.

**Deploy AWS ECS Service:**

Task\_3: Create an ECS service that runs containers using Terraform.

Details: Define task definitions, service configurations, and load balancer integration.

**Create AWS Elastic Beanstalk Application:**

Task\_4: Deploy an Elastic Beanstalk application using Terraform.

Details: Define Elastic Beanstalk environment, application version, and platform.

**Provision AWS Lambda Functions:**

Task\_5: Create AWS Lambda functions using Terraform.

Details: Define Lambda function code, runtime, memory, environment variables, and IAM role.

**Network:** 

**Implement VPC with Public and Private Subnets:**

Task\_1: Set up a VPC with public and private subnets using Terraform.

Details: Define VPC, subnets, route tables, and security groups for isolation.

**Deploy AWS Network Load Balancer:**

Task\_2: Create a Network Load Balancer to distribute traffic at the TCP/UDP layer.

Details: Define NLB, target groups, listeners, and associated resources.

**Create AWS Route 53 DNS Records:**

Task\_3: Configure Route 53 DNS records using Terraform.

Details: Define hosted zone, record sets for A, CNAME, and Alias records.

**Implement VPC Peering:**

Task\_4: Set up VPC peering between two VPCs using Terraform.

Details: Define VPC peering connections, accepter and requester configurations.

**Provision AWS Transit Gateway:**

Task: Create a Transit Gateway to interconnect multiple VPCs and VPNs using Terraform.

Details: Define Transit Gateway, attachments, route tables, and associations.

**Security:**

**Implement AWS Security Groups:**

Task: Create AWS security groups using Terraform.

Details: Define inbound and outbound rules to control traffic flow.

**Set Up AWS WAF Web ACLs:**

Task: Configure AWS Web Application Firewall (WAF) web ACLs using Terraform.

Details: Define WAF rules, conditions, and association with resources.

Provision AWS Identity and Access Management (IAM) Roles and Policies:

**Task: Create IAM roles and policies for EC2 instances and services.**

Details: Define IAM roles, policies, and attach policies to roles.

**Deploy AWS Secrets Manager Secrets:**

Task: Create secrets in AWS Secrets Manager using Terraform.

Details: Define secret values, rotation policies, and permissions.

**Implement AWS Key Management Service (KMS) Keys and Policies:**

Task: Set up AWS KMS keys and policies using Terraform.

Details: Define KMS keys, key policies, and encryption settings.

**Lambda Functions:**

**Create AWS Lambda Function with S3 Trigger:**

Task: Deploy an AWS Lambda function triggered by S3 bucket events using Terraform.

Details: Define Lambda function code, runtime, S3 trigger configuration, and IAM role.

**Implement AWS Lambda Layers:**

Task: Create and manage AWS Lambda layers using Terraform.

Details: Define Lambda layer content, compatible runtimes, and usage.


**Deploy Scheduled AWS Lambda Functions:**

Task: Schedule AWS Lambda functions to run at specified intervals using Terraform.

Details: Define scheduled event rules, Lambda function associations, and IAM role.

**Set Up AWS Lambda Provisioned Concurrency:**

Task: Configure AWS Lambda provisioned concurrency using Terraform.

Details: Define Lambda function settings, concurrency limits, and IAM roles.

**Provision AWS Lambda Functions in VPC:**

Task: Deploy AWS Lambda functions inside a Virtual Private Cloud (VPC) using Terraform.

Details: Define Lambda function settings, VPC configuration, and security groups.

**EKS Cluster:**

**Create Amazon EKS Cluster:**

Task: Set up an Amazon EKS cluster using Terraform.

Details: Define EKS cluster configuration, node groups, networking, and IAM roles.

**Implement EKS Managed Node Groups:**

Task: Create EKS managed node groups for worker nodes using Terraform.

Details: Define node group settings, instance types, and scaling configurations.

**Provision EKS Fargate Profile:**

Task: Create EKS Fargate profiles to run Kubernetes pods without managing nodes using Terraform.

Details: Define Fargate profile settings, selectors, and namespace associations.

**Deploy EKS Cluster with Application Load Balancer Ingress:**

Task: Set up an EKS cluster with ALB ingress controller using Terraform.

Details: Define EKS cluster, ingress resources, ALB settings, and networking.

**Create Kubernetes Namespace Using EKS and Terraform:**

Task: Create a Kubernetes namespace within an EKS cluster using Terraform.

Details: Define Kubernetes namespace and RBAC configurations.

**Storage:**

**Provision Amazon EBS Volumes:**

Task: Create Amazon EBS volumes and attach them to EC2 instances using Terraform.

Details: Define EBS volume settings, type, size, and attachment configurations.

**Implement Amazon S3 Buckets with Versioning:**

Task: Set up Amazon S3 buckets with versioning enabled using Terraform.

Details: Define S3 bucket settings, versioning configuration, and access controls.

**Deploy Amazon RDS Aurora Cluster:**

Task: Create an Amazon RDS Aurora database cluster using Terraform.

Details: Define Aurora cluster settings, instance types, and replication.

**Provision Amazon DynamoDB Tables:**

Task: Deploy Amazon DynamoDB tables with key schema and provisioned throughput using Terraform.

Details: Define DynamoDB table schema, capacity, and access control.

**Set Up Amazon Elastic File System (EFS) File System:**

Task: Create an Amazon EFS file system using Terraform.

Details: Define EFS file system settings, access points, and access control.
