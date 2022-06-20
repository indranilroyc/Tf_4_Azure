# Tf_4_Azure

## Pre req for this repo
### Install github cli with below command and clone the repo
`winget install --id GitHub.cli`

### Open your PowerShell prompt as an administrator and run the following command:
`Invoke-WebRequest -Uri https://aka.ms/installazurecliwindows -OutFile .\AzureCLI.msi; Start-Process msiexec.exe -Wait -ArgumentList '/I AzureCLI.msi /quiet'; rm .\AzureCLI.msi`

### Authenticate using the Azure CLI

`az login`

Once you have chosen the account subscription ID, set the account with the Azure CLI.

`az account set --subscription "subscription-id"`
