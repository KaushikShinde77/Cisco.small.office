# Cisco.small.office

## Objective

The goal of this project is to design and simulate a working and secure small office network using Cisco Packet Tracer. The network uses subnetting to organize IP addresses properly and VLANs to separate departments for better security and easier management. Trunk links are set up so that VLANs can communicate with each other. Inter-VLAN routing has been configured so that devices in different VLANs can talk to each other through a router or Layer 3 switch. Wireless access is available for laptops and tablets to give users more flexibility in how they connect to the network. DHCP is used to automatically assign IP addresses to devices, and DNS is set up only to support DHCP, not for browsing the internet.This project shows key networking concepts like building a clear network layout, setting up VLANs, allowing communication between VLANs, adding wireless connections, and configuring network services. The final result is a small office network that is reliable, organized, and ready to grow if needed.

### Skills Learned 

-Subnetting and IP address planning
-VLAN creation and configuration
-Trunk port setup between switches and routers
-Inter-VLAN routing (router-on-a-stick / Layer 3 switch)
-DHCP server setup for automatic IP assignment
-Basic DNS configuration to support DHCP
-Wireless network setup for mobile devices
-Network troubleshooting and testing using Cisco Packet Tracer
-Designing a structured and scalable network topology

### Steps

I started by putting together all the required devices, i.e. the router, switch, pc's,etc and making basic cable connections.

<img width="1451" height="602" alt="Screenshot 2025-10-19 192758" src="https://github.com/user-attachments/assets/f49a551f-f67f-4fd5-9be3-506b7c83d4fb" />

Next I created Vlan's to assign devices as per their departmental role in the company. To check if the vlan's are properly implemented i used 'do show vlan' to confirm their status. I performed trunking as well so the vlan's can communicate with each other more efficiently.

<img width="711" height="675" alt="Screenshot 2025-07-24 115209" src="https://github.com/user-attachments/assets/183e24c4-9290-41bf-8781-b1f58af473d2" />

<img width="703" height="681" alt="Screenshot 2025-07-24 115223" src="https://github.com/user-attachments/assets/253eb7d9-18aa-4436-85de-9a10d8526853" />

Next is setting up wireless connection between my access points and tablets/laptops. The process is as simple as setting up a password in access point and entering that password into your other device. But in case of laptops you have to first attach 'WPC300N' so it have have wirless access.

<img width="700" height="681" alt="Screenshot 2025-07-24 121106" src="https://github.com/user-attachments/assets/50fd20e4-b8d2-4c00-b973-9f491f4cab63" />

<img width="704" height="693" alt="Screenshot 2025-07-24 121551" src="https://github.com/user-attachments/assets/1a12aa52-52d0-4fa9-b2f7-b25db9dab0a7" />

<img width="708" height="667" alt="Screenshot 2025-07-24 121633" src="https://github.com/user-attachments/assets/fe85a718-1951-4fd2-8509-95103d7b86bc" />

Everything on the switch is done all that remains is configuring the router. In inter-vlan routing you have to create from a singular network interface multiple sub-interfaces. I start with subnetting and assinging block size ip's to each sub-interface.

<img width="790" height="607" alt="Screenshot 2025-10-19 203738" src="https://github.com/user-attachments/assets/ed2ccf95-7128-42d1-9881-1a3859142d12" />



