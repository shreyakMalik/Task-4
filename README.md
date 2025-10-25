# Terraform + Docker (IaC)

It provisions a Docker container locally with Terraform.

## Steps
1. Initialized Terraform with Docker provider.
2. Pulled `nginx:latest` Docker image.
3. Created container mapped to port 8080.
4. Checked container with browser.
5. Destroyed infrastructure.

## Commands Used
- terraform init
- terraform plan
- terraform apply
- terraform destroy