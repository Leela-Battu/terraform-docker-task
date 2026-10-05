\# Task 3: Infrastructure as Code with Terraform



\## Objective



Provision a local Docker container using Terraform.



\## Tools Used



\- Terraform

\- Docker

\- Nginx



\## Terraform Pipeline



```text

Terraform

&#x20;   ↓

Terraform Init

&#x20;   ↓

Terraform Plan

&#x20;   ↓

Terraform Apply

&#x20;   ↓

Docker Container

&#x20;   ↓

Nginx Application

&#x20;   ↓

Terraform Destroy

```



\## Steps Performed



1\. Configured the Docker provider in Terraform.

2\. Created an Nginx Docker image using Terraform.

3\. Created a Docker container using Terraform.

4\. Used `terraform init` to initialize the project.

5\. Used `terraform validate` to validate the configuration.

6\. Used `terraform plan` to preview the changes.

7\. Used `terraform apply` to create the Docker resources.

8\. Checked the Terraform state using `terraform state`.

9\. Tested the application using `http://localhost:8080`.

10\. Used `terraform destroy` to remove the resources.



\## Files



\- `main.tf` - Terraform configuration

\- `plan.log` - Terraform plan execution log

\- `apply.log` - Terraform apply execution log

\- `destroy.log` - Terraform destroy execution log

\- `terraform.tfstate` - Terraform state file



\## Result



Successfully provisioned and managed a local Docker container using Terraform.



\## Conclusion



This task demonstrates Infrastructure as Code (IaC) using Terraform to automate Docker container provisioning and management.

