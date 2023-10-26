<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Networking lab (NSGs) </h1>
In this tutorial, we will network labs as well as overview creating our resources within Azure. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)
- Powershell
  

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04
- wwww.portal.azure.com

<h2>High-Level Steps</h2>

- Step 1: Create resource group
- Step 2: Create Windows 10 Virtual Machine VM
- Step 3: Create a Linux (Ubuntu) VM
- Step 4: Use remote desktop to connect to Windows 10 VM
- Step 5: Within Windows 10 VM, install Wireshark
- Step 6: Open Wireshark and filter for ICMP traffic only
- Step 7: 

<h2>Actions and Observations</h2>


![Screenshot 2023-10-25 184930](https://github.com/leticialunaa/networking-lab/assets/146797387/6a6bbb64-42bc-4359-9aff-9e13f09e42a6)

Create a resource within www.portal.azure.com



![Screenshot 2023-10-25 190422](https://github.com/leticialunaa/networking-lab/assets/146797387/5bc97731-3ccd-45e5-bd23-066f4b4a6e9c)

</p>
<p>
Create a Windows 10 Virtual Machine (VM)
  
  * While creating the VM, select the previously created Resource Group

  * While creating the VM, allow it to create a new VM (Vnet) and Subnet
  
![image](https://github.com/leticialunaa/networking-lab/assets/146797387/26d4beb3-4710-4475-a975-ba2cafbf97dc)

Create a Linux (Ubuntu) VM

 * While creating the VM, select the previously created Resource Group and Vnet

  * Observe your VM within Network Watcher

  
![image](https://github.com/leticialunaa/networking-lab/assets/146797387/9c3c9ca7-1798-40f6-8f67-8f64c726fed5)

Use Remote Desktop to connect to your Windows 10 VM






<p>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
