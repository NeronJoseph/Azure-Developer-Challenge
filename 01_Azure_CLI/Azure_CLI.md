# Azure CLI 

<p>
Azure CLI is the command line tool from Azure by which we can communicate with Azure cloud. Azure CLI is available for different types of OSes like 
Windows, Linux, MacOS, etc. We can also using Docker images of Azure CLI too. 
</p>

## Install Azure CLI

<p> 
This section helps to install Azure CLI to your local machine. As I'm using Linux machine, the steps I'm sharing will also be linux based. For other OS, I'm sharing the link here to install Azure CLI 
</p>

> Link: https://docs.microsoft.com/en-us/cli/azure/install-azure-cli 

In this directory, you can see a shell script file called `install-azure-cli.sh`. Using that script, we can install Azure CLI on an Ubuntu based machine. 

## Sign into Azure CLI

<p>
Before using Azure CLI, you need to authenticate the Azure CLI installed in your local machine with your Azure Cloud portal. In order to do that, run the following commands:
</p>

```
az login
```
<p>
Then login to Azure portal using the browser. Once the login is successful, we can see a folder with name `.azure` is created at the home directory. 
</p>