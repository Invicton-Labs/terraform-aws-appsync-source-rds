# Terraform AWS Appsync Data Source - RDS

This module creates an AppSync datasource for RDS, which is not currently supported by `aws_appsync_datasource`. Once [this pull request](https://github.com/hashicorp/terraform-provider-aws/pull/9337) is merged and released, this module will no longer serve a purpose.

It uses CloudFormation internally to create and manage the datasource resource.