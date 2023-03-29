terraform {

  cloud {
    organization = "vbouiller-org"

    workspaces {
      name = "webapp-staging-us-west"
    }
  }


  required_providers {
    aws = {
      source  = "hashicorp/aws"
      version = "> 4.59.0"
    }
  }

  required_version = ">= 0.14.0"
}
