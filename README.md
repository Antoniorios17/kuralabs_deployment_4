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
The EC2 doesn't need to be part of the vpc, we are trying to connect the jenkins server from outside the VPC with an agent
	@@ -29,72 +24,6 @@ The EC2 doesn't need to be part of the vpc, we are trying to connect the jenkins
* Connect to the repository on github using personal token
* Test to verify authentication is successful

## Install Jenkins on an EC2
## Install terraform on the EC2
## Configure credentials on Jenkins
## Create a pipeline build on Jenkins
## Create a VPC with terraform and deploy the application
## Additions
## Diagram


# Additions
## Webhook
* To make the current configuration more automated you can connect jenkins to the github repository:
