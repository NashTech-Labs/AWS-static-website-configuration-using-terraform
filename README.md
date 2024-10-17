# AWS-static-website-configuration-using-terraform

This Terraform configuration sets up an Amazon S3 bucket to host a static website. It includes the necessary resources to manage the bucket, configure website hosting, and apply the correct permissions for public access.

## Prerequisites

- [Terraform](https://www.terraform.io/downloads.html) installed on your local machine.
- An AWS account with the necessary permissions to create S3 buckets.

## Configuration

Before applying the Terraform configuration, you need to define the required variables. You can do this by creating a `variables.tf` file or by passing them through the command line.

### Required Variables

- `region`: The AWS region where the S3 bucket will be created.
- `bucket_name`: The name of the S3 bucket (must be globally unique).
- `index_document`: The name of the index document (usually `index.html`).
- `error_document`: The name of the error document (usually `error.html`).

### Example `variables.tfvars`

```hcl
Replace the values of bucket name and region
region="replaceme"
bucket_name="replaceme"