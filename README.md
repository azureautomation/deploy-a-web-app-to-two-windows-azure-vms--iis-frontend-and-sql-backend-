Deploy a Web App to Two Windows Azure VMs (IIS Frontend and SQL Backend)
========================================================================

            

[Windows Azure Scripting Center](http://www.windowsazure.com/en-us/documentation/scripts) |
[Get Started with Windows Azure PowerShell](http://go.microsoft.com/fwlink/?linkid=320929&clcid=0x409) |
[Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Description

Creates two virtual machines; a front-end Windows Server and a back-end SQL server.


The front-end server is configured with the Web Platform Installer, which is then used to install an application published on the Web Platform Installer catalog.


The back-end SQL server is configured with 'Mixed' mode authentication and a Firewall rule for remote access.


Both Virtual Machines are placed in a single subnet.

Example
 
Scenario
You need to create an environment that pre-installs an application from the Web Platfom Installer (for example, Blogengine.net) and connect the Virtual Machine to a new SQL server instance.
Requirements

  *  PowerShell Version 3.0 
  *  Windows Azure PowerShell 0.6.18 
See Also

  *  [RemoteScripts.ps1](https://github.com/WindowsAzure/azure-sdk-tools-samples/blob/master/solutions/infrastructure/RemoteScripts.ps1)

  *  [BlogengineNet.app](https://github.com/WindowsAzure/azure-sdk-tools-samples/blob/master/solutions/infrastructure/BlogengineNet.app)

  *  [Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Script Content

The content of the script is reproduced below

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
