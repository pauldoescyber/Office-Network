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

# DHCP pool configuration on router
I also configured DHCP on the router for the networks that had multiple members i.e the sales department(192.168.1.0) and the IT department(192.168.2.0).Below is the set of commands I used to configure the dhcp on the router for both of the interfaces.
<img src="https://github.com/user-attachments/assets/3097b483-2963-4506-aecf-66b9e43cb55a" height ="80%" width ="80%" alt="Setting up an interface on the router">
<br />
<br />






