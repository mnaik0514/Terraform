# **main.tf:**

Is the main configuration file where we host modules and commands on what we would like to deploy int the env.

login to azure cloud using:
az login

## **Terraform Workspaces:**

Way to create seperate instances of state data within the same working directory.

## **Terraform State:**

- The state file maps real world resources to your configuration.
- Keeps track of metedata and improves performance for large infrastructure.
- they are in JSON
- locally stored in a local file called terraform.tfstate
- can be stored remotely using Azure storage Account, Cloud, S3 bucket etc.
- refreshes to update the state with the real infrastructure.

## **Terraform Resources:**

## **Terraform Commands:**

**terraform init:**
Prepares working directory for other commands

**terraform validate:**
Checks weather the configurations is valid
validates variables or typos

**terraform plan:**
show all the changes taking place by the current configurations
what we are going to create or update using our infrastructure as code

**terraform apply:**
Also runs **terraform plan:** when executed
actually create or updates the infrastructure

**terraform destroy:**
Destroys previously created infrastructure

**terraform -help:**
gives a quick overview of the commands

**terraform workspace show**
shows the workspace that we are working in.

**terraform workspace list:**
List all the workspaces we have

**terraform workspace new workspace_name**
creates  a workspace in terraform

**terraform workspace select workspace_name:**
To switch to a specific workspace


