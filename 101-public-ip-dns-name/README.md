# Create a public IP with DNS Name

<a href="https://azuredeploy.net/" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template allows you to create a public IP with DNS Name during the template deployment. This is a template snippet. For a more complete network definition, see this template:

https://github.com/Azure/azure-quickstart-templates/tree/master/101-loadbalancer-with-nat-rule

Below are the parameters that the template expects

| Name   | Description    |
|:--- |:---|
| dnsNameForPublicIP  | Unique DNS Name for the Public IP used to access the Virtual Machine. |
| location | location where the resources will be deployed |

