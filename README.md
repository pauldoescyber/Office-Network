# Office network.
This is an office network topology built on Cisco packet tracer to mimic an office network enviroment. 
# Project Description.
Here I built an office network on cisco pakcet tracer consisting of two departments each under two different networks(sales and IT), a web server on its own network and a DNS server that would resolve the name of the website hosted by the web server(www.myoffice.com). The router (router0) has been configured for DHCP and hence assigned IP addressed dynamically to the hosts on the two office networks..that is the sales(192.168.1.0) and IT(192.168.2.0)department.

# Utilities used.
<li>DNS</li>
<li>DHCP</li>
<li>HTTP</li>
<li>Subnetting</li>
<li>Networking</li>

# Enviroment
<li>Cisco packet tracer</li>

# Project overview
An overview of the project.

<img src="https://github.com/user-attachments/assets/bd6d5e4e-3839-4434-865e-1eebe777fc22" height ="80%" width ="80%" alt="Overview of networking project for a small office">
<br />
<br />

# Network Topology on Cisco Packet tracer
<img src="https://github.com/user-attachments/assets/6fc55d60-9840-4248-a5fa-58c429558acc" height ="80%" width ="80%" alt="Network Topolgy">
<br />
<br />

# Router configuration
For the project the first things to do after physically connecting the hosts,servers and switches(for my project I used copper-straight through wire for the host pcs and copper cross over for the servers) is to configure the interfaces on the router which by default are adminstratively down as well as provide each interface with an IP address.Below is a screenshot of the commands I used to configure one of the interfaces.
<img src="https://github.com/user-attachments/assets/8839f79e-6142-4044-87ff-bee9a17d9b97" height ="80%" width ="80%" alt="Setting up an interface on the router">
<br />
<br />

# DHCP Configuration on router
I also configured DHCP on the router for the networks that had multiple members i.e the sales department(192.168.1.0) and the IT department(192.168.2.0).Below is the set of commands I used to configure the dhcp on the router for both of the interfaces.
<img src="https://github.com/user-attachments/assets/3097b483-2963-4506-aecf-66b9e43cb55a" height ="80%" width ="80%" alt="Setting up an interface on the router">
<br />
<br />
# Testing DHCP
After configuring the DHCP service on my router I tested it by requesting for an IP address from a host to be assigned dynamically.This was sucessful as denoted by the screenshot showed below.
<img src="https://github.com/user-attachments/assets/f4b1a8aa-e570-4892-880a-2314e0880372" height ="80%" width ="80%" alt="Setting up an interface on the router">
<br />
<br />
# Setting up the Web server.
First I had to statically assign the server with an IP addressing information as shown below.
<img src="https://github.com/user-attachments/assets/be0dc1f2-3687-4cef-8423-31b665bad02a" height ="80%" width ="80%" alt="Static IP of Web server">
<br />
<br />
For this I selected the services option and turned on HTTP. I then edited the index.html file to fit the services being offered by the website.
<img src="https://github.com/user-attachments/assets/eda66d9a-d06b-4137-9cad-a53da49f42fd" height ="80%" width ="80%" alt="Setting up Web server Information">
<br />
<br />
# DNS Configuration on server
 I had to configure the DNS server to resolve a Domain name (www.myoffice.com) and doing this involved giving the server an address.I did this statically. And then going to the services menu turning on DNS 
 and registering the IP address of the web server (which I had already pre-planned to be 192.168.3.2 ) as 192.168.3.2 associated with the site www.myoffice.com The following screen shots show this information.
 <br />
 Manually giving the server an IP address
 <img src="https://github.com/user-attachments/assets/ca89b3de-edeb-4a32-b6bd-32bbf9ae57ac" height ="80%" width ="80%" alt="Manually assigning IP address to server">
<br />
<br />
Setting up DNS services and registering the domain name and IP address resoluition
 <img src="https://github.com/user-attachments/assets/3a1840c9-8238-4730-9e74-09cbdb9987e8" height ="80%" width ="80%" alt="Setting up DNS services">
<br />
<br />
# Testing DNS services
To ensure DNS was operational, I pinged the website from one of the hosts and on doing so recieved a reply as shown below.
<img src="https://github.com/user-attachments/assets/1db71b3e-98d5-4b80-97bf-999111a55bed" height ="80%" width ="80%" alt="Setting up DNS services">
<br />
<br />
# Testing the entire network.
To conduct the final test of the entire network, From one of the hosts using the web browser I visited the website www.myoffice.com which was successful
and that showed the proper funcitioning of DHCP, DNS and the web server. The screen shot from this visit is shown below.
<img src="https://github.com/user-attachments/assets/353631a9-0edf-4484-9df7-78bb6361071d" height ="80%" width ="80%" alt="Testing the entire network">
<br />
<br />






