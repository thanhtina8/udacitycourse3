## Introduction
This is the project for the Udacity Cloud DevOps using Microsoft Azure Nanodegree Program, in this project we create disposable test environments and run a variety of automated tests with the click of a button. Additionally, we monitor and provide insight into an application's behavior, and determine root causes by querying the application’s custom log files.

For this project we use the following tools:

- Azure DevOps: For creating a CI/CD pipeline to run Terraform scripts and execute tests with Selenium, Postman and Jmeter
- Terraform: For creating Azure infrastructure as code (IaS)
- Postman: For creating a regression test suite and publish the results to Azure Pipelines.
- Selenium: For creating a UI test suite for a website.
- JMeter: For creating a Stress Test Suite and an Endurance Test Suite.
- Azure Monitor: For configuring alerts to trigger given a condition from an App Service.

## Getting Started
For this project we will follow the next steps:
1. Install our dependencies
2. Configure storage account and state backend for Terraform
3. Configure Pipeline Environment
4. Configure an Azure Log Analytics Workspace

## Install our dependencies
| Dependency | Link |
| ------ | ------ |
| Terraform | https://www.terraform.io/downloads.html |
| JMeter |  https://jmeter.apache.org/download_jmeter.cgi|
| Postman | https://www.postman.com/downloads/ |
| Python | https://www.python.org/downloads/ |
| Selenium | https://sites.google.com/a/chromium.org/chromedriver/getting-started |
| Azure DevOps | https://azure.microsoft.com/en-us/services/devops/ |

## Terraform
1.  Clone source code from Github repo
2.  Open a Terminal and connect to your Azure account to get the Subscription ID
3. Create a storage account to Store Terraform state.
4. Copy the storage_account_name, container_name, and access_key, and update the corresponding values in terraform/environments/test/main.tf accordingly.

