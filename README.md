# arm-templates

Template Creates a Windows 10 VM with Visual Studio 2017.

1. Create a resource group
2. Deploy ARM Template: 
New-AzureRmResourceGroupDeployment -Name <enter_name> -ResourceGroupName <rg_name> -TemplateFile .\vs-dev-vm.json -TemplateParameterFile .\azuredeploy-parameters.json -Debug
