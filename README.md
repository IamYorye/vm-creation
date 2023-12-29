<p align="center">
<img src="https://i.imgur.com/OI988z4.png" alt="VM LOGO"/>
</p>

<h1> Azure - Virtual Machine Creation</h1>
This tutorial outlines how to create a virtual machine on Azure and remote desktop connect to that virtual machine. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows Windows 10 (21H2)

<h2>List of Prerequisites</h2>

- Computer with Internet connection
- Azure account with credits (Can create a new account and obtain $200)
- Remote Desktop Connection

<h2>Installation Steps</h2>

Head over to your local web browser and search for portal.azure.com.

<p align="center">
<img src="https://i.imgur.com/plMdnMb.png" alt="Portal Azure"/>
</p>

>**Note**: Notice our resources, we currently have a subscription called azure subscription 1. Be sure to have a subscription before continuing onwards.

Next we'll use azure's search bar to search for virtual machines, under the services tab and click on virtual machines to be navigated to the next section.

<p align="center">
<img src="https://i.imgur.com/Jf6PsPH.png" height="70%" width="70%" alt="search"/> </p>

Now we'll click on the create button and be sure to create an azure virtual machine (first on the list).

<p align="center">
<img src="https://i.imgur.com/A6FV5tv.png" height="70%" width="70%" alt="creation"/> </p>

Now we're on the virtual machine creation page where it may seem like a lot but really some sections get automatically filled out and it's up for the user (you) to decide on what subscription you may want to link this virtual machine to. If you have a new account it will be one subscription. If you haven't created a resource group, one will be automatically created and the virtual machine will be put into that resource group. Create a name for the virtual machine (you can call it whatever you want). Next select any server region you may want, depending on what you want to do you can select any server. Lastly, select the image, would you want to be on windows, ubuntu, etc.

<p align="center">
<img src="https://i.imgur.com/PHr3Kov.png" height="70%" width="70%" alt="vm main page"/> </p>

<p align="center">
<img src="https://i.imgur.com/uvJA9NS.png" height="70%" width="70%" alt="sub and resource group"/> </p>

<p align="center">
<img src="https://i.imgur.com/k28SNwV.png" height="70%" width="70%" alt="instance details"/> </p>

<p align="center">
<img src="https://i.imgur.com/ZwPgHu1.png" height="70%" width="70%" alt="image"/> </p

Onto the next section of crating our virtual machine. We need to create a username and password we'll be using later with Remote Desktop Connection to connect into this virtual machine. Feel free to create any username and password, but make sure to note it for later. Scroll down to the bottom, check mark the licensing tab and we can move onto the the disks section.

<p align="center">
<img src="https://i.imgur.com/6ID9Y16.png" height="70%" width="70%" alt="user and pass"/> </p

<p align="center">
<img src="https://i.imgur.com/GpnE3ny.png" height="70%" width="70%" alt="check"/> </p

We can skip the disks section and go straight to the networking section.

Here we'll only really do one thing and that's either select a different virtual network than the one being created.

<p align="center">
<img src="https://i.imgur.com/w6F1Ae0.png" height="70%" width="70%" alt="network"/> </p

<p align="center">
<img src="https://i.imgur.com/M0ARlEI.png" height="70%" width="70%" alt="review and create"/> </p

Now we'll finally create our virtual machine by clicking the create button on the bottom left of the screen.

<p align="center">
<img src="https://i.imgur.com/nWeFzOO.png" height="70%" width="70%" alt="create"/> </p

We have our virtual machine created now! Navigate back to your virtual machines and now you should see the new virtual machine you created.

<p align="center">
<img src="https://i.imgur.com/6TpQ5nq.png" height="70%" width="70%" alt="new vm"/> </p

Now it's time for us to connect to our virtual machine by first grabbing the public IP address. Cick on your VM and make sure to copy the public ip address for remote desktop connection.

<p align="center">
<img src="https://i.imgur.com/Ad3aQyP.png" height="70%" width="70%" alt="IP"/> </p

<p align="center">
<img src="https://i.imgur.com/b4LelId.png" height="70%" width="70%" alt="copy of IP"/> </p

On the bottom left opf your desktop click the microsoft logo, which is the start menu and type in remote desktop connection.

<p align="center">
<img src="https://i.imgur.com/QdlHXq1.png" height="70%" width="70%" alt="micro"/> </p

Take that Public IP Address you have previously copied from your virtual machine and paste it into the computer section of remote desktop connection and press connect.

<p align="center">
<img src="https://i.imgur.com/sxZVtkP.png" height="70%" width="70%" alt="copy paste"/> </p

You're now naviagted towards a new pop up to enter you credentials. Remember that username and password we create while creating our virtual machine, it's time to put that to use and fill out that information here to connect to our virtual machine.

<p align="center">
<img src="https://i.imgur.com/JIyCGZH.png" height="70%" width="70%" alt="creds"/> </p

Don't worry about thisnext pop up, just click yes.

<p align="center">
<img src="https://i.imgur.com/JIyCGZH.png" height="70%" width="70%" alt="yes"/> </p















                                                                                  










