# CI/CD Practice Project

Tools Used: Ansible, Circleci, Cloudformation, Docker, AWS

# Steps followed in the project

1. Set up a project repository on github

2. Proceed to set up a new project on CircleCI associated with the github repository

3. Set up Environment Variables by creating and IAM User with programmatic access on AWS and input the values to the project on CircleCI

4. Create the CloudFormation template

5. Create the CircleCI Config file

The CircleCI config file include the jobs and step to create the infrastructure

6. Push your local change to the remote Github repo. Your commits will automatically trigger a CircleCI build.

# What was achieved in this project

Creating a CI/CD pipeline which catch build error, test error and error in any dependencies early using CircleCI

Creating an infrastructure template using IAC tool

Deploying and Configuring our infrastucture using a configuration management tool Ansible
