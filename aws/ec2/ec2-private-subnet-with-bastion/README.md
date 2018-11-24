# Secure EC2 instance in private subnet with a bastion

The template defines 
- a secure EC2 instance in a private subnet
- NAT gateway to private unidirectional access form the private 
subnet to the internet for secured resources
- bastion instance to setup ssh tunnel to secured instance 
- routes and security groups for all resources to control open ports and traffic to/from VPN resources 
