Terraform setting block:

terraform {
  required_version = "~> 1.0"         1.1.4/5/6/7   1.2/3/4/5 1.1.4/5/6/7
  required_providers {
    aws = {
      source  = "hashicorp/aws"
      version = "~> 3.0"
    }
  }
  backend "s3" {
    bucket = "terraform-mylandmark"
    key    = "prod/terraform.tfstate"
    region = "us-west-2"
    dynamodb_table = "terraform-lock"
  }
}
