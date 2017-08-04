#Virtual Machine Creation with Multi NICs


<a href="https://portal.azure.cn/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcathyhxz%2Fazure-quickstart-templates%2Fmaster%2F20170801Homework%2FVM-1NIC.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

One-NIC Virtual Machine Creation using One Subnets


Multi-NIC Virtual Machine Creation using Two Subnets
<a href="https://portal.azure.cn/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcathyhxz%2Fazure-quickstart-templates%2Fmaster%2F20170801Homework%2FVM-2NICs.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

Multi-NIC Virtual Machine Creation using Two Subnets
<a href="https://portal.azure.cn/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcathyhxz%2Fazure-quickstart-templates%2Fmaster%2F20170801Homework%2FVM-2PublicIP.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template creates a new VM with two NICs which connect to two different subnets within the same VNet.

## Tips
1. If running under PowerShell you may update the **azuredeploy.parameters** file with the **allowedValues** for the subnet name of the Primary NIC and Secondary NIC for a nice dropdown list.
2. Customize parameters in **azuredeploy.parameters** as you see appropriate, at the very least the **adminPassword**.

Feel free to post qeustions and enjoy!
