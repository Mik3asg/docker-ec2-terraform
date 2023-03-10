# NGIX server in a Docker Container on AWS EC2 with Terraform Project

## A fully functional example project showing how to use Terraform to build, run and deploy a Docker Container with NGIX on AWS EC2

This project is an example that was built along with an online course showing how to automate with Terraform (as Infrastructure as Code) the deployment of a NGIX server in a Docker Container on AWS EC2 instance. Every part of this project is sample code which shows how to do the following steps:

* Create a Git Repository for our Terraform Project
* Create an AWS VPC (Virtual Private Cloud) and Subnets
* Create Route Table and Internet Gateway
* Associate Subnets with Route Table
* Use AWS Default Compoments: Default Route Table
* Create Security Group
* Fetch Amazom AMI (Amazom Machine Image) for EC2 Instance
* Provision an EC2 Instance
* Create a SSH key pair
* Configure EC2 to run a script for Docker Container

