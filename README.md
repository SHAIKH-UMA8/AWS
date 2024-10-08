# AWS

## Introduction to AWS
In 2006, Amazon Web Services (AWS) began offering IT infrastructure services to businesses as web services—now commonly known as cloud computing. One of the key benefits of cloud computing is the opportunity to replace upfront capital infrastructure expenses with low variable costs that scale with your business. With the cloud, businesses no longer need to plan for and procure servers and other IT infrastructure weeks or months in advance. Instead, they can instantly spin up hundreds or thousands of servers in minutes and deliver results faster.

Today, AWS provides a highly reliable, scalable, low-cost infrastructure platform in the cloud that powers hundreds of thousands of businesses in 190 countries around the world

## 1.IAM (Identity and Access Management)
AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. With IAM, you can manage permissions that control which AWS resources users can access. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources. IAM provides the infrastructure necessary to control authentication and authorization for your AWS accounts.

## 2.EC2 Instances
Amazon Elastic Compute Cloud (Amazon EC2) provides on-demand, scalable computing capacity in the Amazon Web Services (AWS) Cloud. Using Amazon EC2 reduces hardware costs so you can develop and deploy applications faster. You can use Amazon EC2 to launch as many or as few virtual servers as you need, configure security and networking, and manage storage. You can add capacity (scale up) to handle compute-heavy tasks, such as monthly or yearly processes, or spikes in website traffic. When usage decreases, you can reduce capacity (scale down) again.
### Features of Amazon EC2
*Instances
Virtual servers.

*Amazon Machine Images (AMIs)
Preconfigured templates for your instances that package the components you need for your server (including the operating system and additional software).

*Instance types
Various configurations of CPU, memory, storage, networking capacity, and graphics hardware for your instances.

*Amazon EBS volumes
Persistent storage volumes for your data using Amazon Elastic Block Store (Amazon EBS).

*Instance store volumes
Storage volumes for temporary data that is deleted when you stop, hibernate, or terminate your instance.

*Key pairs
Secure login information for your instances. AWS stores the public key and you store the private key in a secure place.

*Security groups
A virtual firewall that allows you to specify the protocols, ports, and source IP ranges that can reach your instances, and the destination IP ranges to which your instances can connect.

## 3.AWS Networking (VPC)
With Amazon Virtual Private Cloud (Amazon VPC), you can launch AWS resources in a logically isolated virtual network that you've defined. This virtual network closely resembles a traditional network that you'd operate in your own data center, with the benefits of using the scalable infrastructure of AWS.

### Features
The following features help you configure a VPC to provide the connectivity that your applications need:

*Virtual private clouds (VPC)
A VPC is a virtual network that closely resembles a traditional network that you'd operate in your own data center. After you create a VPC, you can add subnets.

*Subnets
A subnet is a range of IP addresses in your VPC. A subnet must reside in a single Availability Zone. After you add subnets, you can deploy AWS resources in your VPC.

*IP addressing
You can assign IP addresses, both IPv4 and IPv6, to your VPCs and subnets. You can also bring your public IPv4 addresses and IPv6 GUA addresses to AWS and allocate them to resources in your VPC, such as EC2 instances, NAT gateways, and Network Load Balancers.

*Routing
Use route tables to determine where network traffic from your subnet or gateway is directed.

*Gateways and endpoints
A gateway connects your VPC to another network. For example, use an internet gateway to connect your VPC to the internet. Use a VPC endpoint to connect to AWS services privately, without the use of an internet gateway or NAT device.

*Peering connections
Use a VPC peering connection to route traffic between the resources in two VPCs.

*Traffic Mirroring
Copy network traffic from network interfaces and send it to security and monitoring appliances for deep packet inspection.

*Transit gateways
Use a transit gateway, which acts as a central hub, to route traffic between your VPCs, VPN connections, and AWS Direct Connect connections.

*VPC Flow Logs
A flow log captures information about the IP traffic going to and from network interfaces in your VPC.

*VPN connections
Connect your VPCs to your on-premises networks using AWS Virtual Private Network (AWS VPN).

## 4.AWS Lambda
AWS Lambda is a flexible service designed for a wide variety of use-cases. Across the millions of AWS customers using Lambda every month, serverless applications generally fall into several common categories:

## 5.Amazon S3

Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. Customers of all sizes and industries can use Amazon S3 to store and protect any amount of data for a range of use cases, such as data lakes, websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics. Amazon S3 provides management features so that you can optimize, organize, and configure access to your data to meet your specific business, organizational, and compliance requirements.

## Amazon RDS
Amazon Relational Database Service (Amazon RDS) is a web service that makes it easier to set up, operate, and scale a relational database in the AWS Cloud. It provides cost-efficient, resizable capacity for an industry-standard relational database and manages common database administration tasks.






