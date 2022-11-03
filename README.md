# logicapp-attachments-to-blob

> This template creates an logic app that you can use to store attachements with specific file extensions (e.g. `.xls`) to Azure Blob Storage.

## Quick Start

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fasad-shmoghadam%2Flogicapp-attachments-to-blob%2Fmain%2Fazuredeploy.json)

## Prerequisites

- An Azure account and subscription. If you don't have an Azure subscription, sign up for a free Azure account.

- An email account from an email provider supported by Logic Apps, such as Office 365 Outlook, Outlook.com. For other providers.

- An Azure Storage account. If you don't have an Azure Storage account, create one. and setup a container for the attachments.

- An Azure Logic App resource

- An Azure Function for removing HTML from the body of the email, you can use [Function A - RemoveHTML](https://github.com/asad-shmoghadam/az-func-a-remove-html)
