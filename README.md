# Sample AWS CloudFormation Templates
The templates are addressed to different deployment cases and organized by AWS services: Elastic Compute Cloud (EC2), Elastic Container Service (ECS),
Elastic Beanstalk, please go `./aws/ec2`, `./aws/ecs` or `./aws/beanstalk` to see the templates.

You should be able to find a README file for each case along with the template. The README should give you
a brief description of that particular case.

Feel free to use either `aws cli` or AWS Console (Web UI) to deploy the templates. 

## Beanstalk
1. [Beanstalk application in a public subnet](aws/beanstalk/beanstalk-public-subnet)

## EC2
1. [Secure EC2 instance in a private subnet with a bastion host](aws/ec2/ec2-private-subnet-with-bastion)

## ECS
1. [Secure ECS cluster in a private subnet](aws/ecs/ecs-fargate-private-subnet)

## RDS
1. [RDS cluster in a private subnet](aws/rds/rds-cluster-in-private-subnet)
1. [RDS serverless cluster](aws/rds/rds-cluster-severless)

## Transcribe
1. [Speech transcription](aws/transcribe/transcribe-voice)
