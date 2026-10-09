# Task 3: Infrastructure as Code with Terraform

This project demonstrates Infrastructure as Code (IaC) by provisioning and managing a Docker container using Terraform.

---

## Objective

Provision and manage a local Docker container using Terraform.

## Tools Used

- Terraform
- Docker
- Nginx

## Terraform Workflow

    Terraform Configuration
             ↓
       Terraform Init
             ↓
      Terraform Validate
             ↓
       Terraform Plan
             ↓
       Terraform Apply
             ↓
       Docker Container
             ↓
       Nginx Application
             ↓
      Terraform Destroy

---

## Steps Performed

1. Configured the Docker provider in Terraform.
2. Defined an Nginx Docker image using Terraform.
3. Created a Docker container using Terraform.
4. Initialized the project using `terraform init`.
5. Validated the configuration using `terraform validate`.
6. Previewed the infrastructure changes using `terraform plan`.
7. Created the Docker resources using `terraform apply`.
8. Inspected the Terraform state using `terraform state`.
9. Accessed the Nginx application through the configured local port.
10. Removed the Docker resources using `terraform destroy`.

---

## Project Files

- `main.tf` - Terraform configuration file.
- `plan.log` - Terraform plan execution log.
- `apply.log` - Terraform apply execution log.
- `destroy.log` - Terraform destroy execution log.
- `.terraform.lock.hcl` - Records the selected Terraform provider versions.

---

## Result

Successfully provisioned and managed a local Nginx Docker container using Terraform.

## Conclusion

This project demonstrates Infrastructure as Code (IaC) by automating Docker container provisioning and management with Terraform.
