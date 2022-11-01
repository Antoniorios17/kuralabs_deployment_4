# kuralabs_deployment_4
Terraform deployment 4

# Table of contents


1. Install Jenkins on an EC2
2. Install terraform on the EC2
3. Configure credentials on Jenkins
4. Create a pipeline build on Jenkins
5. Create a VPC with terraform and deploy the application
6. Additions
7. Diagram

![tables](<link>)

## Install Jenkins on an EC2
* Create an EC2 
* Select an ubuntu image
* Most settings can be left on default
* Security groups:
  * open ports 80, 22 and 8080
* Install jenkins dependencies and then jenkins
* I used an [script](https://github.com/Antoniorios17/kuralabs_deployment_4/blob/main/jenkins-terraform.sh) to automate the process of installation



## Install Jenkins on an EC2
* Create a EC2 with the proper 

## Install terraform on the EC2

## Configure credentials on Jenkins
## Create a pipeline build on Jenkins
## Create a VPC with terraform and deploy the application
## Additions
## Diagram


# Additions
## Webhook
* To make the current configuration more automated you can connect jenkins to the github repository:
