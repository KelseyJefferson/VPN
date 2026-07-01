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
<img width="3766" height="2034" alt="Screenshot 2026-06-24 165125" src="https://github.com/user-attachments/assets/58f179a9-a539-4a1d-8708-fb28b50a760b" />
<img width="3775" height="2047" alt="Screenshot 2026-06-24 165257" src="https://github.com/user-attachments/assets/2cc7745a-0726-4c04-b0da-364a9e3412a9" />

<p>
 Download ProtonVPN to your Windows 10 and Connect to the server. 
<img width="3809" height="2036" alt="Screenshot 2026-06-24 170433" src="https://github.com/user-attachments/assets/247d190f-dae5-4f95-bc57-49a7365ca4e7" />
<img width="3820" height="2016" alt="Screenshot 2026-06-24 170550" src="https://github.com/user-attachments/assets/c93f247c-09c2-4970-8ebf-db381df0b20d" />
<img width="3766" height="2011" alt="Screenshot 2026-06-24 170613" src="https://github.com/user-attachments/assets/6c329004-cdf4-4e50-9e2d-85f3d8535403" />
<img width="3820" height="2052" alt="Screenshot 2026-06-24 170643" src="https://github.com/user-attachments/assets/6e7f5efe-8fe7-4a3b-809d-da49132f359c" />
<img width="3829" height="2016" alt="Screenshot 2026-06-24 170705" src="https://github.com/user-attachments/assets/0f61fff6-3626-46e3-ba30-56f3ceff4313" />

<p>
  Once your connected to a server, Refresh Whatismyipaddress.com and your new VPN ip dadress should pop up. Throughout this lab, you should've seen the 3 times that your IP address has changed.

<img width="3060" height="1842" alt="image" src="https://github.com/user-attachments/assets/8f2d05ec-606b-40a1-96a6-cdf0fbcfce5c" />
<img width="3107" height="1939" alt="image" src="https://github.com/user-attachments/assets/832b0ab1-14a1-481d-9239-14b903df6733" />
<img width="3811" height="2038" alt="Screenshot 2026-06-24 171819" src="https://github.com/user-attachments/assets/8eb1271a-5712-4ace-97ea-314f1f1fbf65" />
<img width="3816" height="2043" alt="Screenshot 2026-06-24 172031" src="https://github.com/user-attachments/assets/813fa1ab-ba78-468a-b8c8-739e1192e31f" />




  
</p>



</p>
<br />
