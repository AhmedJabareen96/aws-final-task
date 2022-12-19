[![](https://www.datocms-assets.com/2885/1620155444-blog-library-product-terraform-aws.jpg)](https://www.datocms-assets.com/2885/1620155444-blog-library-product-terraform-aws.jpg)

# AWS Terraform Final Task

**create Terraform code for building the following environment it includes:**

- 2 Load Balancers - Internet Facing and Internal - Create and use a Terraform module
- 4 Web Servers - Create and use a Terraform module
- 4 Application Servers - Create and use a Terraform module
- 1 RDS with two nodes (MySQL)
- 1 S3 Bucket
  Assume VPC and subnets already exist "use the default!".
  [![](https://github.com/MariamDghaim/AWS-Terraform-Final-Task-/blob/main/Capture.PNG?raw=true)](https://github.com/MariamDghaim/AWS-Terraform-Final-Task-/blob/main/Capture.PNG?raw=true)

---

## At the very beginning, run the command:

'aws configure'
and enter your credentials in order to connect to aws.

---

**Init terraform enivroment:**

```
terraform init

```

---

**To create an execution plan for your infrastructure run:**

```
terraform plan

```

---

**To apply the changes outlined in an execution plan to your infrastructure run:**

```
terraform apply

```

---

**To destroy the resources created by Terraform run:**

```
terraform destroy

```

---
