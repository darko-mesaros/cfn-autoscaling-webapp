# CloudFormation Sample Autoscaling application

A sample AWS CloudFormation template that creates a few things:
- VPC with all its configuration
- An EC2 Autoscaling Group
- Application Load Balancer in front of it all

It also comes with the `buildspec.yml` file to be used with a CI/CD pipeline for infrastructure deployment.

There is a separate Stack that creates the entire CI/CD Pipeline and it will/is available *here*.
