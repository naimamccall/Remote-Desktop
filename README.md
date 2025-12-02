<p 
 align="center"><img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/ef0bef94-1338-42c3-ad37-1b38df5f6e81" />
</p>

<h1>Virtual Machine Setup and Utilization</h1>
This tutorial outlines the setup and ultilization of Remote Desktop<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Powershell

<h2>Operating Systems Used </h2>

- Mac OS
- Windows OS

<h2>List of Prerequisites</h2>

- Step 1: Recource Group Setup and Virtual Machine Configuration.

- Step 2: Locating New IP.
  
- Step 3: Adding New PC to Remote Desktop.
  
- Step 4: Navigation Within The Virtual Machine.

  

<h2>Installation Steps</h2>


<h2>Step 1- Recource Group Setup and Virtual Machine Configuration</h2>
<p>
<img width="3004" height="1944" alt="image" src="https://github.com/user-attachments/assets/d8d69fde-f327-49d1-aae2-99576e76d53d" />
<p>
 Azure allows users to utilize it's environments in versitile ways. One of them being virtual machines. Creating a virtual machine will require proper configuration to insure the system runs proficiently. In order to build a virtual machine, you must start by creating a recource group. Make sure to give the recourse group a unique name. A virtual machine name must be established as well as a region and zone. An image must be selected which will determine what OS will be working when using the virtual machine. For the sake of this lab Windows 11 will be selected. A username and password will be established for the virtual machien in this page as well, it is important to keep note of what username and password is ultimately used. It is important to check of the box at the bottom of this section for confirmation.
</p>
<br />

<h2>Step 2- Locating New IP</h2>
<p>
<img width="2024" height="964" alt="image" src="https://github.com/user-attachments/assets/2f3fe04f-f8d9-4eb1-9bce-a5ad21011f4a" />
</p>
<p>
Once the virtual machine has been established it can be explored. It has its own IP address you can looke for when clicking on it, seperate from the IP being used on the physcial computer that created the virtual machine. Before entering the virtual machine it's vital to click the start button so it can begin running. Azure is a pay as you go service so when virtual machines are not being used it is important to stop them in order to save money. Once the VM is running the IP address can be copied.
</p>
<br />

<h2>Step 3- Adding New PC to Remote Desktop</h2>
<p>
<img width="1538" height="1070" alt="image" src="https://github.com/user-attachments/assets/72e7c431-def1-4533-8a8e-c553c9d51c1c" />
</p>
<p>
Remote Desktop will be used to enter the virtual machine that has been created. Upon opening Remote Desktop a new PC will be added.
</p>
<p>
<img width="868" height="668" alt="image" src="https://github.com/user-attachments/assets/ef5bff4f-8bd9-4e99-b0fe-bde50f3ad1d6" />
</p> 
<p>
<img width="984" height="692" alt="image" src="https://github.com/user-attachments/assets/48be315d-3cad-4a2c-a81b-5961f5fe4fa2" />
</p>  
<p> 
The PC will include the IP address from the virtual machine as its PC name along with a friendly name to easily keep track. The username and password that was entered when creating the virtual machine will be re entered in remote desktop as the last step before entering the environment.
</p>
<br />

<h2>Step 4- Navigation Within The Virtual Machine</h2>
<p>  
<img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/6e9fa65c-cd83-4287-99e5-ed9fcb983ce0" />
</p>
<p>
After the proper login information is entered access into the computer will be granted. As a Mac user I now have Windows OS features at my disposal without having to switch physical PCs.
</p>
<br />

<p>  
<img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/83ba0fff-3ce5-48eb-98c7-3b5aa7f1bf3e" />
</p>
<p>  
<img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/1aec517c-65a5-437c-bf16-26cf16a3e0df" />
</p>
<p> 
Once remoted into this virtual machine powershell can be accessed. If ipconfig /all is typed in it can be noticed that the information of the computer that is being mirrored shows up instead of the information of the physical PC the user is on.
</p>
<br />

