# Sample AWS CloudFormation Templates
The templates are addressed to different deployment cases and organized by AWS services: Elastic Compute Cloud (EC2), Elastic Container Service (ECS),
Elastic Beanstalk, please go `./aws/ec2`, `./aws/ecs` or `./aws/beanstalk` to see the templates.

You should be able to find a README file for each case along with the template. The README should give you
a brief description for that particular case.

Feel free to use either `aws cli` or AWS Console (Web UI) to deploy the templates. 

## Beanstalk
1. [Beanstalk application and secure RDS instance in private subnet](aws/beanstalk/beanstalk-private-subnet-with-rds)

## EC2
1. [Secure EC2 instance in private subnet with a bastion](aws/ec2/ec2-private-subnet-with-bastion)

## ECS
1. [Secure ECS cluster in private subnet with serverless RDS cluster](aws/ecs/ecs-fargate-cluster-rds-serverless)
