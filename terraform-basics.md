"# Terraform Basics" 
# Terraform Basics

Terraform lets you create cloud infrastructure from code.

## Main commands
- `terraform init` : downloads the provider plugins and sets up the folder
- `terraform fmt` : cleans up the formatting of your files
- `terraform validate` : checks the code for errors
- `terraform plan` : shows what will be created or changed
- `terraform apply` : creates the infrastructure
- `terraform destroy` : deletes everything Terraform created

## Small example (main.tf)
```
provider "aws" {
  region = "us-west-2"
}

resource "aws_s3_bucket" "example" {
  bucket = "my-unique-bucket-name-12345"
}
```

## Workflow
init, then plan, then apply