rkamisetti/basic infra-structure - cloudformation tempalte

This infrastructure repository contains opinionated AWS CloudFormation templates for creating and managing VPC, SubNets, Security Group, Route Tables(Private & Public), ELB, NATGateway, EIP Elastic IPAddress etc.,

The template has been tailored to run basic infrasturcture as staging and production environments for small-to-medium size businesses and price points.

Resources available in infrastructure.yaml templates:

1. Elastic load balancer
2. VPC with private and public subnets across two availability zones
3. Application Load Balancer in front on the EC2 Instances
4. Security Groups locking resources down to just those that need them

Adapted from awslabs/ecs-refarch-cloudformation and awslabs/ecs-refarch-continuous-deployment.
