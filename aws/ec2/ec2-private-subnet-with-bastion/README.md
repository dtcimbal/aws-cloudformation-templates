# Secure EC2 instance in a private subnet with the bastion

The template defines 
- Secure EC2 instance in a private subnet
- The NAT gateway to provide unidirectional access form a private 
subnet to the internet for secured resources
- A bastion instance to setup ssh tunnel to the secured instance 
- Routes and security groups for all resources to control open ports and traffic to/from VPC resources 
