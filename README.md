![image](https://github.com/danielbangm/azure-ressources/assets/22795502/074de211-4659-4e32-93b0-52a7f8eed69e)

<h1>Azure ressources - Prerequisites and ressource creation</h1>
This tutorial creates some compute and networking ressources in Microsoft Azure and do some networking activities.

<h2>Environment and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used</h2>

- Windows 10
- Ubuntu

<h2>List of Prerequisites</h2>

- All you need for this lab is the Azure Tenant and Subscription

<h2>Installation steps</h2>

- Step 1: Go to www.portal.azure.com and create your subcription
- Step 2: Click on the search bar and tap "ressource group" 
- Step 3: Create a new ressource group and name it RG-Lab-01
  ![image](https://github.com/danielbangm/azure-ressources/assets/22795502/4533e18f-1b9a-4f31-a499-26624f53f0ca)
- step 4: Click on the search bar and tap "Virtual Machine"
- Step 5: Create a new Virtual Machine
<p>
Create 2 Virtual Machines(one using Windows 10 and another using Linux specifically Ubuntu. You also want to choose at least 2 Virtual CPU for your VMs. Use username and passwords you won't forget). Choose our Ressource Group (RG-Lab-01 we created earlier as the default ressource group.
</p>

![image](https://github.com/danielbangm/azure-ressources/assets/22795502/539ce16e-235c-44eb-9eea-d7fcd0ca9ae5)

<p>
  Automatically, these VMs have Network Security Groups(NSG) attached to the network adapter. This is essentially for all intent and purposes of firewall and we'll be doing few configurations on this firewall in the second part of this lab. Your VMs will have a public IP address(which we will use to remote access the VM) and a private IP address. Both VM will be in the same virtual network. 
</p>

![image](https://github.com/danielbangm/azure-ressources/assets/22795502/cd6bca44-03b7-4a27-a257-8057ebd08c29)

![image](https://github.com/danielbangm/azure-ressources/assets/22795502/db0f203e-66b9-43d8-b8ce-767c9411498f)

![image](https://github.com/danielbangm/azure-ressources/assets/22795502/d25b3223-b566-4447-aa81-45054308a402)

![image](https://github.com/danielbangm/azure-ressources/assets/22795502/47453b01-eee4-482f-9314-236322319708)

<p>
  As we can see these VMs have different public IP addresses and private addresses, They are in the same Virtual network/subnet: VM1-vnet/default.
We will use these VMs in the next part of this lab!
</p>


