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
STEP 6 (RENAMING CLIENT DEVICE): <br/>
<img src="https://i.imgur.com/38kv6So.png" height="70%" width="70%"/> </p>


<p align="center">As you can see, the Client device has been renamed. I have renamed it "DEKSTOP2".</p>

<a href="https://www.example.com">
  <button>NEXT</button>
</a>
