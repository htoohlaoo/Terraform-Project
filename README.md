# Terraform Basic Commands

The four fundamental Terraform commands used to manage infrastructure as code.

### 1. `terraform init`

Initializes the working directory containing the Terraform configuration files. This command downloads necessary provider plugins, configures the backend, and prepares the environment for future Terraform operations.

### 2. `terraform plan`

Generates and displays an execution plan. It allows you to preview the changes that Terraform will make to your infrastructure based on the current state and the provided configuration. No changes are made when running `terraform plan`.

### 3. `terraform apply`

Applies the changes required to reach the desired state of your configuration. This command will create, update, or destroy resources according to the execution plan.

### 4. `terraform destroy`

Removes all the resources defined in your Terraform configuration. This command will delete the infrastructure, essentially rolling back any changes made by `terraform apply`.
