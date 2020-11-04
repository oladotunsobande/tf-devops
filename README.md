# TF-DevOps

This is a platforms and infrastructure provisioning for AWS and co. using Terraform.

## Setup

Clone this repository by running the following command:

```
$ git clone https://github.com/oladotunsobande/tf-devops.git
```

Set all environment variables as highlighted in `terraform.tfvars.sample` file.
NOTE: Ensure you create a `terrafrom.tfvars` and set your variables

To view the infrastructure provisioning plan, run the following command:

```
$ terraform plan
```

To effect/execute the plan, run the following command:

```
$ terrform applu
```

## Platforms

The various platforms that will be covered are as follows:

```
Amazon Web Services (AWS)
Google Cloud Platform (GCP)**
```

** - this feature is coming soon

### Amazon Web Services (AWS)

The `aws.tf` file creates 2 EC2 instances with Ubuntu server AMIs, a load balancer and corresponding security groups.