# -EC2-Deployment-with-Terraform
I wrote a Terraform configuration that defined an EC2 instance (“t2.micro”) using a specific Amazon Machine Image (AMI). This ensured that the instance had the required operating system and configuration.

I followed the standard Terraform workflow:

<terraform init> : This was my starting point, initializing the working directory, downloading the AWS provider, and getting everything ready for deployment. 

<terraform plan> : I then created an execution plan to preview the changes Terraform would make. 

<terraform apply> : I executed the plan and created the EC2 instance.

<terraform destroy> : To clean up resources and avoid unnecessary costs, I used terraform destroy to delete the EC2 instance. This command ensured that all the infrastructure I created was properly removed, and it was a valuable part of understanding the full lifecycle management of cloud resources.
