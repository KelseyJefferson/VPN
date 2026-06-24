# Using a VPN Through an Azure Virtual Machine 
<p align="center">
<img width="1440" height="919" alt="Screenshot_8-5-2026_163346_www bing com" src="https://github.com/user-attachments/assets/d351b08c-aaf0-4692-957d-95474b4cadf5" />
</p>

This tutorial shows a walkthrough on  how to use a Virtual Private Network and how it changes your IP Address.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN
- Whatsmyipaddress.com

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2> VPN Process </h2>

- Finding IP address
- Creating a Virtual Machine
- Downloading ProtonVPN

<h2>Walk-Through</h2>

<p>
 First, you will locate your main IP Address on Wheresmyipaddress.com. You will copy down your IPv4 for future reference. 

 <img width="3800" height="1851" alt="screenshot-1778342764410" src="https://github.com/user-attachments/assets/f379e1e1-97ca-479a-a606-e8a5edc60254" />
<br />


<p>
  Next, you will create a resource group on Microsoft Azure by clicking the resource tab in the left-hand corner. You will then title your group "VPN_LABS", click review, and when everything looks correct, click create.
<img width="3558" height="1733" alt="Screenshot_22-6-2026_18457_portal azure com" src="https://github.com/user-attachments/assets/f49b05c9-a1b6-4df7-8938-ada3bc58e5f4" />
<img width="3823" height="2146" alt="screenshot-1" src="https://github.com/user-attachments/assets/61d579bf-364b-413d-a697-d874378186e6" />
<img width="3718" height="1828" alt="Screenshot_29-4-2026_195621_portal azure com" src="https://github.com/user-attachments/assets/f6494370-88d9-485e-b111-f4dc609a0ff2" />
</p>
<br />


<p>
 After creating your resource group, you will then create your virtual machine. You will put your subscription in the resource group that you created and name it "Github". Next, set your region to (US) West US 3 and set it to Zone 1. You will create your username and password however you like. Connect to Windows 10, click Confirm on the licensing screen. When you finish, click review and create. 
<img width="3558" height="1733" alt="Screenshot_29-4-2026_195739_portal azure com" src="https://github.com/user-attachments/assets/a6ad5d01-257d-48c5-b3f1-5ae1c0044ac8" />
 <img width="3558" height="1733" alt="Screenshot_29-4-2026_202227_portal azure com" src="https://github.com/user-attachments/assets/86c1391d-c5a3-4aa1-b9c8-85bf374476f2" />
 <img width="3558" height="1733" alt="Screenshot_29-4-2026_202255_portal azure com" src="https://github.com/user-attachments/assets/76a2d4f3-9f1f-49f7-a07d-6d192518c33e" />
 </p>


  Once your virtual machine is up and running, you will log in to your remote desktop connection with your virtual machine's public network and open your browser. You will pull back up Whatismyipaddress.com and locate your virtual machine's IPv4 address. 
<img width="3813" height="2045" alt="Screenshot 2026-06-24 164418" src="https://github.com/user-attachments/assets/ece97c70-c561-4da7-b846-c7ea84767494" />
<img width="2250" height="1389" alt="Screenshot 2026-06-24 164452" src="https://github.com/user-attachments/assets/a57bf52b-3757-4dba-98ae-84afcfdda015" />
<img width="2536" height="1472" alt="Screenshot 2026-06-24 165017" src="https://github.com/user-attachments/assets/c54ffb9d-ecfd-46b8-9359-00f58af91cc8" />

</p>
Find your Virtual Machines IP Address on Whatismyipaddress.com and write it down. 
<img width="3821" height="1890" alt="screenshot-1778190957759" src="https://github.com/user-attachments/assets/986e83c4-b7c4-40a3-92c1-c846d183d9f2" />


<p>
 Download ProtonVPN to your Windows 10 and Connect to the server. 
<img width="3840" height="2160" alt="Annotation 2026-05-08 211605" src="https://github.com/user-attachments/assets/f75a9927-e1b9-4d01-942f-67aa463d245a" />


<p>
  Once your connected to a server, Refresh Whatismyipaddress.com and your new VPN ip dadress should pop up. Throughout this lab you should've seen the 3 times that you IP address has changed.
 <img width="3393" height="2937" alt="Screenshot_8-5-2026_212235_whatismyipaddress com" src="https://github.com/user-attachments/assets/42b9a6a1-bbd1-4375-a116-594daf2caa4f" />
  
</p>



</p>
<br />
