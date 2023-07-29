# aws_pipeline
CI/CD pipelines - Automated CI/CD - AWS AutoScaling Group Deployment

This repository has a CloudFormation template for deploying an EC2 AutoScaling group with a basic web server installed.

The web server serves a simple web page that displays the version number of the deployment. 
This version number is updated automatically whenever changes are made to the repository, 
using a CI/CD pipeline implemented with GitHub Actions.
