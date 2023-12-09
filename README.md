# AWS_COMPLETE_GUID

AWS_COMPLETE_GUID for devops engineers to learn AWS in 30 Days. This repo includes projects, presentations, interview questions and real time examples. Each day's class will provide real-time knowledge on AWS services, allowing you to apply what you've learned and gain practical skills in working with AWS in a DevOps context.

# **Day 1: Introduction to AWS**

You will learn what is private and public cloud. Why companies are moving to public cloud, what are the advantages of moving to cloud.

Also, you will be introduced to the basics of AWS, including the core services and their significance in DevOps practices. Finally learn how to set up an AWS account and navigate the AWS Management Console.

# **Day 2: IAM (Identity and Access Management)**

You will explore IAM, which is used for managing access to AWS resources. You'll learn how to create IAM users, groups, and roles, and how to apply permissions and security best practices to ensure proper access control.

# **Day 3: EC2 Instances**

You'll dive into EC2, which provides virtual servers in the cloud. You'll learn how to launch EC2 instances, connect to them using SSH, and understand key concepts such as instance types, security groups, and key pairs.

Your First AWS Project: Deploy a simple web application(such as jenkins) on the ec2 instance and access the application from outside AWS.

# **Day 4: AWS Networking (VPC)**

You'll explore AWS networking concepts, with a specific focus on VPC (Virtual Private Cloud). You'll learn how to create and configure VPCs, subnets, and route tables, enabling you to design and manage the network infrastructure for your applications.

# **Day 5: AWS Security**

This day emphasizes security best practices in AWS. You'll learn how to implement security measures such as security groups, network ACLs (Access Control Lists), and IAM policies to ensure the confidentiality, integrity, and availability of your AWS resources.

# **Day 6: AWS Route 53**

Project: Configure and manage a domain name using Route 53. You'll register a domain, set up DNS records, and explore advanced features such as health checks, routing policies, and DNS-based failover.

# **Day 7: Secure VPC Setup with EC2 Instances**

Project:

Design and configure a VPC: Create a VPC with custom IP ranges. Set up public and private subnets. Configure route tables and associate subnets.

Implement network security: Set up network access control lists (ACLs) to control inbound and outbound traffic. Configure security groups for EC2 instances to allow specific ports and protocols.

Provision EC2 instances: Launch EC2 instances in both the public and private subnets. Configure security groups for the instances to allow necessary traffic. Create and assign IAM roles to the instances with appropriate permissions.

Networking and routing: Set up an internet gateway to allow internet access for instances in the public subnet. Configure NAT gateway or NAT instance to enable outbound internet access for instances in the private subnet. Create appropriate route tables and associate them with the subnets.

SSH key pair and access control: Generate an SSH key pair and securely store the private key. Configure the instances to allow SSH access only with the generated key pair. Implement IAM policies and roles to control access and permissions to AWS resources.

Test and validate the setup: SSH into the EC2 instances using the private key and verify connectivity. Test network connectivity between instances in different subnets. Validate security group rules and network ACL settings.

By implementing this project, you'll gain hands-on experience in setting up a secure VPC with EC2 instances, implementing networking and routing, configuring security groups and IAM roles, and ensuring proper access control. This project will provide a practical understanding of how these AWS services work together to create a secure and scalable infrastructure for your applications.

# **Day 8: AWS Interview Questions on EC2, IAM and VPC**

# **Day 9: Amazon S3**

This day focuses on Amazon S3, a scalable object storage service. You'll learn how to create S3 buckets, upload and download objects, and organize data using S3 features like versioning, lifecycle policies, and access control.

# **Day 10: AWS CLI**

# **Day 11: AWS CloudFormation**

This day introduces Infrastructure as Code (IaC) using AWS CloudFormation. You'll learn how to create CloudFormation templates to automate the provisioning of resources, manage stacks, and ensure consistent infrastructure across deployments.

Project: You'll work on creating a CloudFormation template that provisions a fully configured application stack, including EC2 instances, networking components, and security groups.
