Copyright (c) <a href="ittaskforce.co.nz">IT Task Force Limited</a>. All rights reserved.

# Create a new SharePoint 2019 Farm with 3 VMs

This template creates three new Azure VMs, each with a public IP address and load balancer and a VNet, it configures one VM to be an AD DC for a new Forest and Domain, one with SQL Server 2017 domain joined and a third VM with a SharePoint 2019, all VMs have public facing RDP

Click the button below to deploy    
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://github.com/ittaskforce-nz/azure-remotedesktop-deployment/mainTemplate.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png" alt="Deploy Environment in Azure" />
    </a>



<a href="http://ittaskforce.co.nz/contact" target="_blank">
    <img src="http://click-it.nz/images/azure.png" alt="Contact IT Task Force" /></a>
</a>

Notes: Sharepoint farm name must not contain spaces.

#https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FNikCharlebois%2Fazure-quickstart-templates%2Fmaster%2Fsharepoint2019-non-ha%2FmainTemplate.json