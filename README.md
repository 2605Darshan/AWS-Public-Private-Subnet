# AWS-Public-Private-Subnet
VPC (Virtual Private Cloud): A logically isolated section of the AWS Cloud where you can define and provision AWS resources. It's your own virtual network within AWS.
Subnets
1.Public Subnet: Connected to the internet via an Internet Gateway (IGW). Resources in this subnet can send and receive traffic directly from and to the internet.
2.Private Subnet: Not directly connected to the internet. Resources in a private subnet can access the internet via a NAT Gateway or NAT Instance located in a public subnet, but cannot be accessed directly from the internet.
Key Services and Components:
  1.Internet Gateway (IGW): Allows communication between instances in your VPC and the internet.
  2.NAT Gateway/NAT Instance: Allows instances in a private subnet to initiate outbound traffic to the internet for updates, downloads but prevent the internet from initiating connections with those instances.
  3.Route Tables: Define rules, known as routes, that determine where network traffic from your subnet or gateways is directed.
  4.Security Groups and Network ACLs: Provide security at the protocol and port access level, and at the subnet level, respectively.
