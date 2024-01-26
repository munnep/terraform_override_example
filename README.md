# Terraform override example

This repository shows what you can do with the `override.tf` file

Looking at the `main.tf` file you would expect that module1 would be used. But because there is a `override.tf` that states to use module2. 

Please see the official documentation [here](https://developer.hashicorp.com/terraform/language/files/override)

# Prerequisites

## Install terraform  
See the following documentation [How to install Terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli) version 1.5 or higher


# How to

- Clone the repository to your local machine
```
git clone https://github.com/munnep/terraform_override_example.git
```
- Change your directory
```
cd terraform_override_example
```
- Terraform initialize
```
terraform init
```
- Notice it is downloading module2 instead of module1
```
Initializing the backend...
Initializing modules...
- test in module2
```
- play around with the `override.tf` file
