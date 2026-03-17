# Amazon EC2
`EC2 - (Elastic Compute Cloud)` is an infrastructure as a service offered by AWS.
Amazon EC2 mainly provides the ability to rent virtual machines (instances) in the cloud.
EC2 allows users to `store data using virtual storage (EBS)`, `distribute traffic across multiple instances using load balancing (ELB)`,
and `scale applications automatically using Auto Scaling groups(ASG).`

# EC2 sizing and configuration Option
With EC2, you can choose:
1. The operating system (OS): Linux or Windows.
2. How much compute power and cores (CPU)
3. How much RAM you want
4. How much storage space can it provide, which can be either Network-attached (EBS and EFS) or Hardware-attached (EC2 instance store)
5. Networking: configure the network card speed and assign public IP addresses.
6. Security set firewall rules using security groups.
7. Initialization Scripts use EC2 user data to run scripts at first launch.

# EC2 instance types
`t2.micro`, `t2.xlarge`, `cd5.4xlarge`, `r5.16xlarge`, `m5.8xlarge` and many others. With the instance types, choose the instance that best suits your application.
