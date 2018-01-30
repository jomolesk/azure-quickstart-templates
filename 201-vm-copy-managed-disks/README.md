# Multi VM Template with Managed Disk 

<a href="https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fjomolesk%2Fazure-quickstart-templates%2Fmaster%2F201-vm-copy-managed-disks%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/AzureGov.png"/>
</a>

This template will provision N number of virtual machines with your choice in a single VNET. Every VM will be provisioned with a Network Interface and a Public IP resource.  A single storage account will be provisioned to store the diagnostic information. 
If you provision 3 VM’s with this template, your resources will look like below in the resource group. 

![template resources](images/resources.png "template resource objects")

`Tags:Managed Disks, Azure VMs, Copy Index`
