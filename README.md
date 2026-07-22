# Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 22.07.2026		

# Objective:

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required:
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram:

<img width="1920" height="1140" alt="Screenshot 2026-07-22 113256" src="https://github.com/user-attachments/assets/2ec119bb-3ec0-4049-a44a-33127ae54da7" />

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure:
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any):

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results):

<img width="1920" height="1140" alt="Screenshot 2026-07-22 113909" src="https://github.com/user-attachments/assets/1d7c7556-3ddc-44ac-a512-d94bdb618420" />


<img width="1920" height="1140" alt="Screenshot 2026-07-22 113753" src="https://github.com/user-attachments/assets/11a8f8f7-3970-4a03-9ffa-fe3838549c1e" />


________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
