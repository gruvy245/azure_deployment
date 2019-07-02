# Multi-NIC Virtual Machine Creation using Two Subnets
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https:%2F%2Fraw.githubusercontent.com%2Fgruvy245%2Fazure_deployment%2Fmaster%2F101-4nic-csr-vrf-3vnets-peered%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png">
<%2Fa>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fgruvy245%2Fazure_deployment%2Fmaster%2F101-4nic-csr-vrf-3vnets-peered%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io//visualizebutton.png">
<%2Fa>


This template creates a new VM with two NICs which connect to two different subnets within the same VNet.

## Tips
1. If running under PowerShell you may update the **azuredeploy.parameters** file with the **allowedValues** for the subnet name of the Primary NIC and Secondary NIC for a nice dropdown list.
2. Customize parameters in **azuredeploy.parameters** as you see appropriate, at the very least the **adminPassword**.

Feel free to post qeustions and enjoy!