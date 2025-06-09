

<p align="center">
  <img src="https://github.com/user-attachments/assets/cf7db6b2-6e72-41ac-aab4-d1d0074b20cf" alt="image" />
</p>



<h1>Azure VM Creation and VPN Testing Lab</h1>
This tutorial walks you through the process of creating a Virtual Machine (VM) in Microsoft Azure, accessing it via Remote Desktop, configuring ProtonVPN, and exploring how VPN usage impacts your IP address and browsing experience. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN
- Web Browsing

<h2>Operating Systems Used</h2>

- Windows 10 Pro (22H2 - x64 Gen2)

<h2>List of Prerequisites</h2>

- Create and Configure the Azure VM
- Record IP Address from the Azure VM
- Sign Up for ProtonVPN
- Install ProtonVPN in the Virtual Machine
- Record IP Address from the VPN Connection
- Browse Websites and Test VPN Effects

<h2>Installation Steps</h2>

<p>
  
## Step 1: Create and Configure the Azure VM

![image](https://github.com/user-attachments/assets/df48a70c-9386-4d96-967c-462f23352dd9)



</p>
<p>
  
-  Log in to the Microsoft Azure Portal.
- Navigate to Virtual Machines and click Create to set up a new VM.
- Select the following configurations for your VM:
  - Name: **Windows10VM**
  - vCPUs: **2**
  - Username: **LabUser**
  - Password: **cyberlab123!**
  - Logged into the VM using Remote Desktop. Public IP address
- After creation, click on the VM and locate its Public IP Address.
- Use Remote Desktop to connect to the VM
</p>
<br />

## Step 2: Record IP Address from the Azure VM
![image](https://github.com/user-attachments/assets/3d1568fd-ed9f-4b7e-9411-c9b2083cb1f6)

<p>
  
- Logged into the Azure VM using Remote Desktop.
- Opened a browser inside the VM and visited
     - [What is My IP Address](https://whatismyipaddress.com/).
- Recorded the IP address associated with the VM.

</p>
<br />

## Step 3: Sign Up for ProtonVPN

<p>
  
![image](https://github.com/user-attachments/assets/e35d2e5c-ed67-4f85-b1fd-259525cfbd1f)

</p>
<p>
  
- Navigate to ProtonVPN Sign-Up and sign up for a free account.
   - [ProtonVPN Sign-Up](https://account.protonvpn.com/signup?plan=free&language=en).

- Follow the instructions to confirm your email address and activate your ProtonVPN account. 


</p>
<br />

## Step 4: Install ProtonVPN in the Virtual Machine

<p>
  
![image](https://github.com/user-attachments/assets/9b2b7e4b-9584-4c7a-bcdd-8ba741ee2868)


</p>
<p>
  
- Download the ProtonVPN client from the official website.
- Open the downloaded installer and follow the steps to install ProtonVPN in your Azure VM.
- After installation, launch ProtonVPN and log in using your credentials from **Step 3**
</p>
<br />

## Step 5: Press "Connect" To Enable VPN

<p>
  
![image](https://github.com/user-attachments/assets/e72a5c0f-9137-4ca3-8598-e612378f0d2b)


</p>
<p> 
  
- Connect to a VPN server located in a different country (e.g., Japan).
- Observe the new IP address assigned by ProtonVPN. 

</p>
<br />

## Step 6: Record IP Address from the VPN Connection

<p>
  
![image](https://github.com/user-attachments/assets/47839b86-eed5-46ee-8243-6f5327bad4b0)


</p>
<p>
  
- Once connected, [What is My IP Address](https://whatismyipaddress.com/) again to observe the new IP address.
- Record the new IP address assigned by ProtonVPN.

</p>
<br />

## Step 7: Browse Websites and Test VPN Effects

<p>

![image](https://github.com/user-attachments/assets/b51c8f8d-2643-4523-9c65-3356f0ad49ad)


</p>

- With the VPN connection active, browse the following websites inside the Azure VM:
  - [Google](https://www.google.com)
  - [Amazon](https://www.amazon.com)
  - [Disney](https://www.disney.com)
- Observe any changes in website content based on the VPN location. For example:
   - Language preferences might change.
   - Region-specific content or offers might be displayed (e.g., products available only in certain countries).

</p>
<br />

## Conclusion

In summary, deploying a Virtual Machine in Azure and using ProtonVPN to modify your IP address illustrates how geographic location can influence internet browsing. Through this lab, you’ve gained practical experience in using VPNs to observe regional website variations, deepening your understanding of cloud computing, VPN functionality, and online privacy.

![Azure](https://img.shields.io/badge/Azure-Cloud-blue)
