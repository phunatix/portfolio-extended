---
title: OpenTofu
---

OpenTofu is an open source fork of Hashicorp's Terraform since the license changed to BSL with version 1.13. To use it, you need to install the tofu CLI. Usually, all modules are compatible and the HCL syntax works similar to Terraform. 

Once importing and iupgrading, keep in mind you cannot go back to the terraform version; it also creates a separate tofu state file that is different to the terraform state file.