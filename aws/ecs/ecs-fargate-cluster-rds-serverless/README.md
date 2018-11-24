# Secure ECS cluster in private subnet with serverless RDS cluster

The template defines 
- Secure ECS cluster in a private subnet
- Secure RDS serverless Aurora cluster in the same private subnet
- Bastion instance to setup ssh tunnel to secured resources
- Routes and security groups for all resources to control open ports and traffic to/from VPN resources 
