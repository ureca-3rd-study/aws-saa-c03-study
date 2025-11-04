VPC Quiz

Question 1:

You have a corporate network of size 10.0.0.0/8 and a satellite office of size 192.168.0.0/16. Which CIDR is acceptable for your AWS VPC if you plan on connecting your networks later on?


172.16.0.0/12


172.16.0.0/16 <


10.0.16.0/16


192.168.4.0/18

Question 2:

When using VPC Endpoints, what are the only two AWS services that have a Gateway Endpoint available?


Amazon S3 & Amazon SQS


Amazon SQS & DynamoDB


Amazon S3 & DynamoDB <

Question 3:

You would like to provide Internet access to your EC2 instances in private subnets with IPv4 while making sure this solution requires the least amount of administration and scales seamlessly. What should you use?


NAT Instances with Source/Destination Check flag off


Egress Only Internet Gateway


NAT Gateway <

Question 4:

If you want a 500 Mbps Direct Connect connection between your corporate datacenter to AWS, you would choose a .................. connection.


Dedicated


Hosted <

Question 5:

Your company has several on-premises sites across the USA. These sites are currently linked using private connections, but your private connections provider has been recently quite unstable, making your IT architecture partially offline. You would like to create a backup connection that will use the public Internet to link your on-premises sites, that you can failover in case of issues with your provider. What do you recommend?


VPC Peering


AWS VPN CloudHub <


Direct Connect


AWS PrivateLink

Question 6:

You want to scale up an AWS Site-to-Site VPN connection throughput, established between your on-premises data and AWS Cloud, beyond a single IPsec tunnel's maximum limit of 1.25 Gbps. What should you do?


Use 2 Virtual Private Gateways


Use Direct Connect Gateway


Use Transit Gateway <

Question 7:

How can you capture information about IP traffic inside your VPCs?


Enable VPC Flow Logs <


Enable VPC Traffic Mirroring


Enable CloudWatch Traffic Logs

Question 8:

Which AWS service allows you to protect and control traffic in your VPC from layer 3 to layer 7?


AWS Network Firewall <


Amazon Guard Duty


Amazon Inspector


Amazon Shield

Question 9:

You plan on creating a subnet and want it to have at least capacity for 28 EC2 instances. What's the minimum size you need to have for your subnet?


/28


/27


/26 <


/25

Question 10:

You have a VPC in your AWS account that runs in a dual-stack mode. You are continuously trying to launch an EC2 instance, but it fails. After further investigation, you have found that you are no longer have IPv4 addresses available. What should you do?


Modify your VPC to run in IPv6 mode only


Modify your VPC to run in IPv4 mode only


Add an additional IPv4 CIDR to your VPC <

Question 11:

A web application hosted on a fleet of EC2 instances managed by an Auto Scaling Group. You are exposing this application through an Application Load Balancer. Both the EC2 instances and the ALB are deployed on a VPC with the following CIDR 192.168.0.0/18. How do you configure the EC2 instances' security group to ensure only the ALB can access them on port 80?


Add an Inbound Rule with port 80 and 0.0.0.0/0 as the source


Add an Inbound Rule with port 80 and 192.168.0.0/18 as the source


Add an Inbound Rule with port 80 and ALB's Security Group as the source <


Load an SSL certificate on the ALB

Question 12:

You need to set up a dedicated connection between your on-premises corporate datacenter and AWS Cloud. This connection must be private, consistent, and traffic must not travel through the Internet. Which AWS service should you use?


Site-to-Site VPN


AWS PrivateLink


AWS Direct Connect <


Amazon EventBridge

Question 13:

Security Groups operate at the ................. level while NACLs operate at the ................. level.


EC2 instance, Subnet


Subnet, EC2 instance <

Question 14:

A company has set up a Direct Connect connection between their corporate data center to AWS. There is a requirement to prepare a cost-effective secure backup connection in case there are issues with this Direct Connect connection. What is the most cost effective and secure solution you recommend?


Setup another Direct Connect connection to the same AWS region


Setup another Direct Connect connection to a different AWS region


Setup a Site-to-Site VPN connection as a backup <

Question 15:

VPC Peering has been enabled between VPC A and VPC B, and the route tables have been updated for VPC A. But, the EC2 instances cannot communicate. What is the likely issue?


Check the NACL


Check the Route Tables in VPC B <


Check the EC2 instance attached Security Groups


Check if DNS Resolution is enabled

Question 16:

Using a Direct Connect connection, you can access both public and private AWS resources.


True <


False

Question 17:

AWS reserves 5 IP addresses each time you create a new subnet in a VPC. When you create a subnet with CIDR 10.0.0.0/24, the following IP addresses are reserved, EXCEPT ....................


10.0.0.1


10.0.0.2


10.0.0.3


10.0.0.4 <

Question 18:

You have set up a Direct Connect connection between your corporate data center and your VPC A in your AWS account. You need to access VPC B in another AWS region from your corporate datacenter as well. What should you do?


Enable VPC Peering


Use a Customer Gateway


Use a Direct Connect Gateway <


Set up a NAT Gateway

Question 19:

You have attached an Internet Gateway to your VPC, but your EC2 instances still don't have access to the internet. What is NOT a possible issue?


Route Tables are missing entries


The EC2 instances don't have public IPs


The Security Group does not allow traffic in <


The NACL does not allow network traffic out

Question 20:

You have 3 VPCs A, B, and C. You want to establish a VPC Peering connection between all the 3 VPCs. What should you do?


As VPC Peering supports Transitive Peering, so you need to establish 2 VPC Peering connections (A-B, B-C) <


Establish 3 VPC Peering connections (A-B, A-C, B-C)

Question 21:

A web application backend is hosted on EC2 instances in private subnets fronted by an Application Load Balancer in public subnets. There is a requirement to give some of the developers access to the backend EC2 instances but without exposing the backend EC2 instances to the Internet. You have created a bastion host EC2 instance in the public subnet and configured the backend EC2 instances Security Group to allow traffic from the bastion host. Which of the following is the best configuration for bastion host Security Group to make it secure?


Allow traffic only on port 80 from the company’s public CIDR


Allow traffic only on port 22 from the company’s public CIDR <


Allow traffic only on port 22 from the company’s private CIDR


Allow traffic only on port 80 from the company’s private CIDR

Question 22:

When you set up an AWS Site-to-Site VPN connection between your corporate on-premises datacenter and VPCs in AWS Cloud, what are the two major components you want to configure for this connection?


Customer Gateway and NAT Gateway


Internet Gateway and Customer Gateway


Virtual Private Gateway and Internet Gateway


Virtual Private Gateway and Customer Gateway <

Question 23:

What does this CIDR 10.0.4.0/28 correspond to?


10.0.4.0 to 10.0.4.15 <


10.0.4.0 to 10.0.32.0


10.0.4.0 to 10.0.4.28


10.0.0.0 to 10.0.16.0