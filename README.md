
<img src="https://i.imgur.com/nBkHqaM.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />

<h1>How to Setup and Use a VPN | ProtonVPN</h1>



<h2>Description</h2>
<p> In this project, we'll explore how to set up a VPN on an Azure virtual machine. We'll create a VM, install ProtonVPN, and test the VPN connection.</p> <br />
<br />
<p> A Virtual Private Network (VPN) establishes a secure connection between your device and the internet by routing your traffic through an encrypted tunnel. This enhances your security and privacy by masking your IP address and encrypting your data. </p>

<br/>


<h2> Software and Platforms</h2>

- <b>ProtonVPN</b>
- <b>Microsoft Azure</b>

<h2> Setting Up a VPN on an Azure VM </h2>

<p> The first step is to deploy a virtual machine (VM) in the Microsoft Azure cloud. </p>
 <br/>
<img src="https://github.com/user-attachments/assets/2384f985-51dc-4a7a-84c3-4096cfbe6c5d" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://github.com/user-attachments/assets/ad8f89f8-f0e2-4911-a108-74f3687abd9a" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<p> While the VM is being created, visit https://whatismyipaddress.com to obtain your current public IP address and location. Save this information for later comparison. </p>
  <br/>
<img src="https://github.com/user-attachments/assets/19b09fdf-9adc-4bc4-b134-e41b423766fc" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<p> Let's connect to our new VM! Use Remote Desktop Connection to access it.</p>
 <br/>
<img src="https://github.com/user-attachments/assets/ce2a02ef-c0e4-4b81-aa64-d9e2131b278f" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<p> Connect to the VM and navigate to https://whatismyipaddress.com again. Note the new IP address and location, reflecting the VM's location in Canada. (The RDP connection acts similarly to a VPN, tunneling your connection to a remote machine.)</p>
  <br/>
<img src="https://github.com/user-attachments/assets/81f092bd-df9b-4ed6-9822-f67184b02529" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<p> Let's head over to ProtonVPN and create a free account.</p>
  <br/>
<img src="https://github.com/user-attachments/assets/9c256a79-4aed-478f-86da-f0ed4813a194" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<p> Now that your account is ready, let's download the ProtonVPN Windows app. You'll find it in the "Downloads" tab on their website.</p>
 <br/>

<br />

<p> Run the ProtonVPN installer and complete the installation. A pop-up window will appear asking you to sign in with your ProtonVPN account. Enter your email address and password to proceed.</p>
  <br/>
<img src="https://github.com/user-attachments/assets/2c76db84-caea-4976-b5d6-e4ce6d7f8456" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<p> Once you've signed in to the ProtonVPN app, you'll be taken to the main interface. From here, you can choose a VPN server location and initiate a secure connection.</p>
 <br/>
<img src="https://github.com/user-attachments/assets/bbd5df2d-d291-4a72-ad14-4d99b01a973a" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<p>The "Quick Connect" feature automatically connects you to a VPN server based on factors like server load and your location. Click the "Quick Connect" button to initiate the connection.</p>

<img src="https://github.com/user-attachments/assets/03da3ddf-5dcc-4e7a-af79-3567f55d64ee" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<p> The VPN has successfully masked your true location. The IP address website now shows your location as Romania, demonstrating that your internet traffic is being routed through the VPN server.</p>
  <br/>
<img src="https://github.com/user-attachments/assets/17b78bfd-13c9-4425-b9b1-18310c6ced58" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<p> While connected to the VPN, visit websites like 
www.google.com and www.netflix.com and observe any differences in content or behavior compared to accessing them without the VPN.</p>
 <br/>
<img src="https://github.com/user-attachments/assets/c59a3294-1336-4349-9d72-9e5a573c6d62" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://github.com/user-attachments/assets/34a6bfe7-65bd-441e-9db0-d21f31fbadef" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />

<h2> You have successfully set up and used ProtonVPN!</h2>

<b> Success! We've set up ProtonVPN and seen how it changes our online location and opens up new possibilities for content access. </b>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
