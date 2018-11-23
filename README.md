# Azure Kubernetes Service DevOps

This is a lab to create a zero downtime scenario for Azure Kubernetes Service (AKS).

## Prerquisties

- Git
- Docker
- Terraform
- Azure Subscription


## Step 1: Setup an Azure DevOps Project

Azure DevOps Services allows you to easily set up automated pipelines to build, test and deploy your code to any platform. We are going to use Azure DevOps as our default platform. If you don't have an account, you can create one [here](https://azure.microsoft.com/en-us/services/devops/).

![Azure DevOps](./docs/images/devops-project.jpg)

Now you can clone the repository locally:

    git clone https://<organization_name>@dev.azure.com/<organization_name>/<project_name>/_git/<project_name>
