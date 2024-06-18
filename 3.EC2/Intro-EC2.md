<h1> Amazon EC2 (Elastic Compute Cloud)</h1>

- EC2 is one of the virtual machine designed by amazon and it is fully **ELASTIC**
  
-Amazon EC2 (Elastic Compute Cloud) is a core service offered by AWS that provides resizable compute capacity in the cloud. 

-It is designed to make web-scale cloud computing easier for **developers by providing scalable and elastic virtual servers.**


<h2>Key Features of Amazon EC2</h2>


1. **Scalability**:
   
   - **Elastic**: Easily scale up or down based on your application's needs.
     
   - **Auto Scaling**: Automatically adjusts the number of instances in response to the demand.
     

2. **Flexibility**:
   
   - **Instance Types**: A wide variety of instance types optimized for different workloads (e.g., compute-optimized, memory-optimized, storage-optimized).
     
   - **Operating Systems**: Supports multiple operating systems, including various distributions of Linux, Windows, and custom AMIs (Amazon Machine Images).
     

3. **Cost-Effective**:
   
   - **Pricing Models**: Multiple pricing options, including On-Demand, Reserved Instances, and Spot Instances.
     
   - **Pay-as-you-go**: Pay only for the compute capacity you use.
     

4. **Security**:
   
   - **VPC**: Launch instances in a virtual private cloud for network isolation.
     
   - **IAM**: Fine-grained access controls using AWS Identity and Access Management.
     
   - **Security Groups**: Stateful firewall to control inbound and outbound traffic.
     

5. **Storage Options**:
    
   - **EBS (Elastic Block Store)**: Persistent block storage for EC2 instances.
     
   - **Instance Store**: Temporary block storage for ephemeral data.
     
   - **Elastic File System (EFS)**: Managed file storage service that can be mounted to multiple EC2 instances.
     


#### EC2 Pricing Models

1. **On-Demand Instances**:
   - Pay for compute capacity by the hour or second with no long-term commitments.
   - Suitable for applications with unpredictable workloads.

2. **Reserved Instances**:
   - Commit to using EC2 for a one- or three-year term to receive a significant discount.
   - Best for steady-state workloads.

3. **Spot Instances**:
   - Purchase unused compute capacity at a lower price.
   - Suitable for flexible, fault-tolerant applications.

4. **Savings Plans**:
   - Flexible pricing model offering lower prices in exchange for a commitment to a consistent amount of usage (measured in $/hour) for a one- or three-year period.

#### EC2 Storage Options

1. **Elastic Block Store (EBS)**:
   - Persistent block storage volumes that can be attached to EC2 instances.
   - Types include General Purpose SSD (gp2, gp3), Provisioned IOPS SSD (io1, io2), Throughput Optimized HDD (st1), and Cold HDD (sc1).

2. **Instance Store**:
   - Temporary storage that is physically attached to the host machine.
   - Data is lost when the instance is stopped or terminated.

3. **Elastic File System (EFS)**:
   - Managed file storage that can be mounted to multiple EC2 instances simultaneously.

#### Networking

1. **VPC (Virtual Private Cloud)**:
   - Allows you to launch AWS resources into a virtual network defined by you.
   - Provides complete control over your virtual networking environment.

2. **Elastic Load Balancing (ELB)**:
   - Automatically distributes incoming application traffic across multiple instances for fault tolerance and load distribution.

3. **Amazon Route 53**:
   - Scalable DNS and domain name registration service.

#### Security and IAM

1. **IAM Roles and Policies**:
   - Use IAM roles to grant permissions to applications running on EC2 instances to access other AWS resources.

2. **Key Pairs**:
   - Securely connect to your instances using SSH (Linux) or RDP (Windows).

3. **AWS CloudTrail**:
   - Enables governance, compliance, and operational and risk auditing by logging API calls.

#### Monitoring and Management

1. **Amazon CloudWatch**:
   - Monitor EC2 instances and other AWS resources in real-time.
   - Collect and track metrics, collect and monitor log files, and set alarms.

2. **AWS Systems Manager**:
   - Provides operational insights and troubleshooting for AWS resources.
   - Includes features like Run Command, Patch Manager, and Parameter Store.

3. **AWS Auto Scaling**:
   - Automatically adjusts the number of EC2 instances in response to the demand.

4. **Elastic Beanstalk**:
   - PaaS that simplifies the process of deploying and scaling applications.

5. **AWS OpsWorks**:
   - Configuration management service that provides managed instances of Chef and Puppet.

By understanding these key features and components, DevOps engineers can effectively utilize Amazon EC2 to deploy, manage, and scale applications in a secure, cost-effective, and efficient manner.
