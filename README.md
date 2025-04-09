Terraform-GCP
This repository contains Terraform configurations for provisioning and managing infrastructure on Google Cloud Platform (GCP). The configurations are organized into two main directories:

infra/: Contains Terraform scripts for setting up the core infrastructure components.

website/: Contains Terraform scripts for deploying and managing web-related resources.

Usage
Clone the Repository:

git clone https://github.com/GeraldAkenji/Terraform-GCP.git
cd Terraform-GCP
Navigate to the Desired Directory:

Choose between infra or website depending on your deployment needs:

cd infra

cd website
Initialize Terraform:

Initialize the Terraform working directory, which will download the necessary provider plugins:

terraform init
Plan the Deployment:

Create an execution plan to preview the changes Terraform will make to your infrastructure:

terraform plan
Apply the Deployment:

Apply the changes required to reach the desired state of the configuration:

terraform apply
Confirm the prompt with yes to proceed.

Destroy the Deployment (Optional):

If you wish to tear down the infrastructure created by Terraform:

terraform destroy
Confirm the prompt with yes to proceed.

Repository Structure
infra/: Terraform configurations for core infrastructure components.

website/: Terraform configurations for web-related resources.

.gitignore: Specifies files and directories to be ignored by Git.