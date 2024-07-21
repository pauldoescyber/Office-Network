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

# Router configuration
For the project the first things to do after physically connecting the hosts,servers and switches(for my project I used copper-straight through wire for the host pcs and copper cross over for the servers) is to configure the interfaces on the router which by default are adminstratively down as well as provide each interface with an IP address. Below is a screenshot of the commands I used to configure one of the interfaces.

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
<img src="https://github.com/user-attachments/assets/3097b483-2963-4506-aecf-66b9e43cb55a" height ="80%" width ="80%" alt="Setting up an interface on the router">
<br />
<br />
# DNS Configuration on server
 I had to configure the DNS server to resolve the FQDN(www.myoffice.com) and doing this involved giving the server an address.I did this statically. And then going to the services menu turning on DNS 
 and registering the IP address of the web server (which I had already pre-planned to be 192.168.3.2 ) as 192.168.3.2 associated with the site www.myoffice.com. The following screen shot shows this information.
 <img src="https://github.com/user-attachments/assets/43f924a4-9c4e-4c3d-94fd-3b466639cb77" height ="80%" width ="80%" alt="Setting up an interface on the router">
<br />
<br />






