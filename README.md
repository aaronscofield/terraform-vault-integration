# Inject secrets into Terraform using the Vault provider

This repo serves as a companion to the [Inject secrets into Terraform using the Vault provider tutorial](https://developer.hashicorp.com/terraform/tutorials/secrets/secrets-vault).

export TF_VAR_aws_access_key = "..."
export TF_VAR_aws_secret_key = "..."
export VAULT_ADDR = "..."
export VAULT_TOKEN = "..."