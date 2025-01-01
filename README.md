<h1>Assigning IP Addresses (Server, Helpdesk and Client Device)</h1>


<h2>Description</h2>
<p>In this section, I'll add IP addresses for each device inside of the domain. This will allow each device to connect to the domain and communicate with each other. It will also make it easy to identify devices within the domain.</p>


<br />

<h2>Step-by-Step Walk-Through:</h2>


<p align="center"> 
STEP 1 (Adding IP Address for Server Device): <br/>
<img src="https://i.imgur.com/vnlRMWa.png" height="70%" width="70%"/> </p>


<p align="center">In this stage, I'd like to add an IP address for the Windows Server 2016 VM. I want to add it because this is a lab environment and I don't want to make things too complicated for myself. If it obtained an IP address from my actual ISP's DHCP, it would require a lot more configuration. So, to add the IP address, I opened the "CONTROL PANEL" and then selected "VIEW NETWORK STATUS AND TASKS" to access network settings.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 2: <br/>
<img src="https://i.imgur.com/sESNJeb.png" height="70%" width="70%"/> </p>


<p align="center">I'm in the network settings for the Windows Server 2016 device. From here, I choose "CHANGE ADAPTER SETTINGS" to change the IP address manually.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 3: <br/>
<img src="https://i.imgur.com/9NA0FZe.png" height="70%" width="70%"/> </p>


<p align="center">This is the Ethernet adapter where the IP address is assigned; from here, I can assign and alter the IP address. I right-click on it and select "Properties" to view the network adapter settings.</p>

<br />

<p align="center"> 
STEP 4: <br/>
<img src="https://i.imgur.com/35fo3YA.png" height="40%" width="40%"/> </p>


<p align="center">This is the "properties" section for the network ethernet adapter. From here, I click "Properties" again to view the network ethernet adapter's advanced options.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/sytUszc.png" height="40%" width="40%"/> </p>


<p align="center">This section describes the network adapter's properties. In this scenario, I need to select the fourth option, "TCP/IPv4". From there, I can finally assign a new IP address.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/xDWVqAr.png" height="70%" width="70%"/> </p>


<p align="center">I select "USE THE FOLLOWING IP ADDRESS" to add a new static IP address. I then added the new IP address, as shown in the photo above. I've also configured a default gateway and a DNS server IP.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 5: <br/>
<img src="https://i.imgur.com/9LJphVc.png" height="70%" width="70%"/> </p>


<p align="center">I'm using the Command Prompt to check if the IP address has changed. I use the "IPCONFIG" command to examine the IP settings of the network adapter. As you can see, the IP address was successfully changed.</p>


<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 6 (Adding IP Address for Helpdesk Device): <br/>
<img src="https://i.imgur.com/iBvXZsN.png" height="70%" width="70%"/> </p>


<p align="center">I need to add an IP address to the Windows 10 device which will be used by the Helpdesk person so that it can join to the domain. To change the IP address, pick the device's "Ethernet" adapter.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/zjn4g8K.png" height="70%" width="70%"/> </p>


<p align="center">I right-clicked on the Ethernet adapter and chose the "PROPERTIES" option. From there, I can change the IP address. To access IP settings, I selected "TCP/IPv4" from the adapter's properties menu.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/m9XZREk.png" height="70%" width="70%"/> </p>


<p align="center">I successfully assigned a new IP address to the Windows 10 device. I've set the IP address to "192.168.1.3".</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/6Ui5EU4.png" height="60%" width="60%"/> </p>


<p align="center">I'm in the command prompt of my Windows 10 device. I typed "IPCONFIG" to see if the IP address was successfully set, and as you can see, it was.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/vavL8wz.png" height="60%" width="60%"/> </p>


<p align="center">Here, I'm pinging the "Server 2016" device to see whether I can reach it. As you can see, I am able to reach the device, and the pings were successful.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 7 (Adding IP Address for Client Device): <br/>
<img src="https://i.imgur.com/uZIzeYD.png" height="70%" width="70%"/> </p>


<p align="center">Here, I successfully assigned a new IP address to the new "DESKTOP2" device which will be used by the client. I've set the IP address to "192.168.1.5". This ensures that the device is on the same subnet and therefore can be joined to the domain.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/GIFt7fa.png" height="60%" width="60%"/> </p>


<p align="center">I'm at the command prompt for the "DESKTOP2" device. I typed "IPCONFIG" to see if the IP address was successfully set, and as you can see, it was.</p>




<a href="https://www.example.com">
  <button>NEXT</button>
</a>
