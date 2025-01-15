# Setting up a VPN (Virtual Private Network)
<p align="center">
<img src="https://i.imgur.com/MntON5Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--Prerequisites and Installation-->
<h1>VPN - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of using a VPN.<br />

<!--Products or Software used-->
<h2>Environments and Technologies Used</h2>
- A VPN (hide.me)
- VMWare (Virtual Machine)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<!--Tutorial-->
- <h2>STEPS INCLUDED</h2>

- STEP 1 - Locate Local IP
- STEP 2 - Setting Up VM
- STEP 3 - Locating IP Through VM
- STEP 4 - Connecting to VPN Through VM
- STEP 5 - Locating IP Address While VPN is Connected

- <h2>Installation Steps</h2>

STEP 1 — Locate your IP address by going to "www.whatismyipaddress.com," which will show you your local IP address. 

Next, we will set up your virtual machine.


STEP 2 - Set up your Virtual Machine (VM) and ensure it has an internet connection.

In the VM, open a web browser and go to whatismyipaddress.com. This website will display the VM's IP address. EXAMPLE2A
<br />
EXAMPLE 3A
<p>
<img src="https://cdn-0.askleo.com/wp-content/uploads/2021/05/geo-locate.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
STEP 3 – Log Into the VM and Find the IP Address
<p>
Now that we have set up the Virtual Machine we will connect to it using the application “Remote Desktop Connection” (EXAMPLE 3A) and input the IP address for the VM that you have located in the command prompt and then input the set credentials for the VM that you have made. 
  
</p>
<br />
EXAMPLE 3A
<p>
<img src="https://i.imgur.com/YPBkMau.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

STEP 4 – CONNECTING TO VPN (Free Version)

Using the local computer In your browser, go to hide.me and click Pricing. Register for the free tier of service. When you receive the invitation email, activate your account. In your account dashboard, download the VPN client to your VM and install it. After installation, sign in to the app using the hide.me account that you created. The App should look something like the photo. (EXAMPLE 4A)
</p>
<br />

EXAMPLE 4A
<p>
<img src="https://i.pcmag.com/imagery/reviews/05LPlniWsYSaFvNFu6P9tUf-28..v1703796523.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>



Select the desired VPN server location from the available options.
</p>
<br />

EXAMPLE 4B
<p>
<img src="https://hide.me/resources/299/images/pages/software/device_windows.png?v=1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Next we will look at the IP again using the VM browser now that we have connected the VPN to Japan. The website www.whatismyipaddress.com shows yet another IP address using the VPN from Japan. This is quite amazing.
  
</p>
<br />

EXAMPLE 4D
<p>
<img src="https://i.imgur.com/lQsISWb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Looking at this exercise we see that we have utilized 3 different IP addresses just from your local computer to connect to the internet.
1. Home IP 
2. Virtual Machin IP
3. Virtual Machin IP VPN

  
</p>
<br />
If you no longer need the VM, ensure to remove it.
END OF TUTORIAL
