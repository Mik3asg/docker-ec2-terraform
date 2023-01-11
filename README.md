# NGIX server in a Docker Container on AWS EC2 with Terraform Project

## A fully funtional example project showing how to use Terraform to deploy a Docker Container with NGIX on AWS EC2

This project is an example that was built along with an online course showing how to automate with Terraform (as Infrastrcture as Code) the deployment of a NGIC server in a Docker Container on AWS EC2 instance. Every part of this project is sample code which shows how to do the following steps:

* 1- Create an AWS VPC (Virtual Private Cloud) and Subnets
* 2- Create Route Table and Internet Gateway
* 3- Associate Subnets with Route Table
* 4- Use AWS Default Compoments: Default Route Table
* 5- Create Security Group
* 6- Fetch Amazom AMI (Amazom Machine Image) for EC2 Instance
* 7- Provision an EC2 Instance
* 8- Create a SSH key pair
* 9- Configure EC2 to run a script for Docker Container
