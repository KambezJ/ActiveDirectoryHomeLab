<h1>Active Directory Home Lab</h1>


<h2>Description</h2>
<b>Create a Windows Networking Environment by creating an Active Directory using Oracle VirtualBox, which will simulate how a corporate network functions. This is achieved by downloading a Windows Server 2019 ISO on one VM to act as a Domain Controller(DC) and house the Active Directory. The VM housing the DC will get two network adapters; one connected to the Internet and one connected to the Internal/Private Network. Then we will name the servers, Install Active Directory, configure NAT/RAS, and set up a DHCP on the DC. After the DC config is finished, a seperate VM will be created on Oracle VirtualBox using a Windows 10 ISO, which will act as a client. This VM (named CLIENT1) will be connected to the Internal/Private Virtual Box Network and joined to the domain. The Powershell scripts in this repository will be responsible for generating random names, creating users within the network, and adding them to the client network as authorized users. Finally, we will log in to the Client Network using one of the generated domain accounts to make sure the network is configured and functioning correctly. The diagram below is a visual representation of the final network that will be built during this lab.
</b>
<br />
<p align="center">
<img src="https://i.imgur.com/kxQ9N3t.jpeg" height="85%" width="85%" alt="Diagram of what this lab will achieve"/>
</p>


<h2>Languages and Utilities Used</h2>

- <b>PowerShell ISE:</b> Write script to generate random names and create users within the Internal/Private Network.
- <b>Oracle VirtualBox:</b> Set up virtual machine for Domain Controller and Client.
- <b>Server Manager:</b> Configure Internal Network, set up DHCP, enable Remote Access and Routing.
- <b>Command Prompt:</b> Check work to ensure IP addresses match (ipconfig) and users are generated successfully (whoami).


<h2>Environments Used</h2>

- <b>Windows 10 ISO:</b> Used for the Client VM.
- <b>Windows Server 2019 ISO</b> Used for Domain Controller VM.


<h2>Program Walk-through</h2>

<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>


<p align="center">
<b>Step 1: Download Oracle VirtualBox and its associated Extension Pack.</b> <br/>
<img src="https://i.imgur.com/n7taX3i.png" height="85%" width="85%" alt="Step 1"/>
</p>
