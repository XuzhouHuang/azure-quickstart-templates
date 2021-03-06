# Virtual Machine Creation with Multi NICs

## One-NIC Virtual Machine Creation
<a href="https://portal.azure.cn/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcathyhxz%2Fazure-quickstart-templates%2Fmaster%2F20170801Homework%2FVM-1NIC.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template creates a new VM with just one NICs which connects to a subnet in a VNet.

## Two-NIC Virtual Machine Creation
1. <a href="https://portal.azure.cn/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcathyhxz%2Fazure-quickstart-templates%2Fmaster%2F20170801Homework%2FVM-2NICs.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template creates a new VM with two NICs which connect to two different subnets within the same VNet.

2. <a href="https://portal.azure.cn/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcathyhxz%2Fazure-quickstart-templates%2Fmaster%2F20170801Homework%2FVM-2PublicIP.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template creates a new VM with two NICs which connect to two different subnets within the same VNet and separate public IPs.


## Tips
1. Customize **parameters** as you see appropriate including VMname, userName and userPassword.

Feel free to post qeustions and enjoy!
