The CloudFormation template defines 
- secure ECS cluster in a private subnet
- secure RDS serverless Aurora cluster in the same private subnet
- bastion instance to setup ssh tunnel to secured resources
- routes and security groups for all resources to control open ports and traffic to/from VPN resources 
