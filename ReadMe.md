# Lab 6 – Scale and Load Balance Your Architecture

## Author

### Name: Mohamed Zabir Khan A
### Register Number: 212224230162

## Title

Scale and Load Balance Your Architecture



## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.



## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection



## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch



## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.



## Workflow (To be filled by Student)

1.Review the existing EC2-based application architecture to understand current deployment, resource usage, and scalability requirements before implementing automation.

2.Create a Launch Template that defines EC2 configuration such as AMI, instance type, key pair, security group, and user data. This ensures consistent instance creation in scaling environments.

3.Create an Auto Scaling Group (ASG) using the launch template. Configure minimum, maximum, and desired capacity to automatically manage the number of running instances based on demand.

4.Set up an Application Load Balancer (ALB) and create target groups to distribute incoming traffic evenly across EC2 instances, ensuring high availability and fault tolerance.

5.Attach the ASG to the load balancer, configure scaling policies using CloudWatch alarms (based on CPU utilization), and test by generating traffic to verify automatic scaling and load balancing.

## Output Screenshots 

<img width="1918" height="842" alt="image" src="https://github.com/user-attachments/assets/756680e7-a6cb-40d2-be52-bab96d8e40d5" />

<img width="1917" height="838" alt="image" src="https://github.com/user-attachments/assets/a4f19557-5a0a-43ea-8623-f53f7baeaa48" />

<img width="1918" height="840" alt="image" src="https://github.com/user-attachments/assets/3b9d1313-ff04-497b-88aa-bc78fd473cfb" />

<img width="1918" height="953" alt="image" src="https://github.com/user-attachments/assets/05183c70-f68e-4b41-bfdc-968e8515b171" />

<img width="1600" height="937" alt="image" src="https://github.com/user-attachments/assets/14ec1297-7309-493c-af57-2a4c3010614c" />

## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
