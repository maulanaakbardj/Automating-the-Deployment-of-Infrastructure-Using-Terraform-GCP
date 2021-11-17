# Automating-the-Deployment-of-Infrastructure-Using-Terraform-GCP
Terraform enables you to safely and predictably create, change, and improve infrastructure. It is an open-source tool that codifies APIs into declarative configuration files that can be shared among team members, treated as code, edited, reviewed, and versioned.

In this lab, you create a Terraform configuration with a module to automate the deployment of Google Cloud infrastructure. Specifically, you deploy one auto mode network with a firewall rule and two VM instances, as shown in this diagram:


Using the files in order to deploy with those simple commands:
```script
terraform --version
mkdir tfinfra
cd tfinfra/
terraform init
terraform init
terraform fmt
terraform init
terraform plan
terraform apply
```
