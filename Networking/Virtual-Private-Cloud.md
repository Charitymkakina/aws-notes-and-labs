# AWS Networking
Amazon Web Services provides networking services that allow you to securely connect resources in the cloud and to on-premises environments. 
The core of AWS networking is the `Virtual Private Cloud (VPC).` `A VPC spans  multiple Availability Zones.`

# Virtual Private Cloud (VPC)
A VPC is a logically isolated network within AWS where you can launch resources.
Key Features of VPC are:
1. Fully customizable network
2. Control over IP addressing (CIDR blocks)
3. Isolation from other AWS networks
   
# Subnets
Subnets divide a VPC into smaller networks.

Types of Subnets
1. `Public Subnet`: Has access to the internet
2. `Private Subnet`: No direct internet access

Subnets are created within a single Availability Zone.

# Internet Gateway (IGW)
Enables communication between a VPC and the internet
Attached to a VPC
Required for public subnets

# Route Tables
Define how traffic flows within the VPC
Contain rules (routes) for directing network traffic
Controls access to internet gateways or other networks

# Security Groups
Act as virtual firewalls for EC2 instances
Control inbound and outbound traffic
`Security groups are stateful`, meaning outbound traffic is automatically allowed

# Network ACLs (NACLs)
Provide an additional layer of security at the subnet level
`NACLs are stateless, meaning rules must be defined for both inbound and outbound traffic

# NAT Gateway
`Enables instances in a private subnet to securely connect to the internet` while blocking unauthorized inbound traffic. 
It translates private IP addresses to a public Elastic IP, ensuring secure, high-bandwidth outbound traffic without exposing internal resources to the public internet.

# VPC to VPC Connectivity
1. `VPC Peering.`
Connects two VPCs privately
Allows resources to communicate using private IP addresses.

2. `Transit Gateway.`
Transit gateway acts as a centralized hub-and-spoke router for connecting hundreds of VPCs, on-premises networks, and VPNs.

# Hybrid Connectivity
1. `AWS Direct Connect.`
It is a dedicated Private connection between on-premises and AWS. It provides higher bandwidth and a low-latency connection.

2. `VPN (Virtual Private Network).`
Connects on-premises networks to AWS securely over the internet
Uses encrypted connections

# Elastic Load Balancer (ELB)
Distributes incoming traffic across multiple targets such as EC2 instances.

Types:
1. `Application Load Balancer (ALB).`
2. `Network Load Balancer (NLB).`
3. `Gateway Load Balancer (GWLB).`
