# Secure EC2 instance in a private subnet with the bastion

The template defines 
- A secure EC2 instance in a private subnet
- NAT gateway to private unidirectional access form a private 
subnet to the internet for secured resources
- Bastion instance to setup ssh tunnel to secured instance 
- Routes and security groups for all resources to control open ports and traffic to/from VPN resources 
