# NETWORKWALKSSHRUTHI-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP
This repository documents my Cybersecurity Lab Environment Setup, completed as part of my cybersecurity internship training with NetworkWalks Academy.

Lab Setup Procedure

Step 1: Install 7-Zip
Installed 7-Zip, if needed, to extract the compressed Kali Linux virtual machine files.

Step 2: Install Oracle VirtualBox
Installed Oracle VirtualBox to create, configure, and manage virtual machines.
VirtualBox provides a virtualized environment for running Kali Linux without installing it directly on the host operating system.

Step 3: Obtain and Import Kali Linux
Obtained the appropriate Kali Linux virtual machine image from the official Kali Linux website and imported it into VirtualBox.

Step 4: Configure the Virtual NAT Network
Created a dedicated NAT Network in VirtualBox.
Example configuration:
Network Name: NatNetwork
IPv4 Network: 10.0.0.0/24
Gateway: 10.0.0.1
A NAT Network can allow multiple connected virtual machines to communicate with each other while providing outbound network access.

Step 5: Configure the Kali Linux Network Adapter
Connected the Kali Linux virtual machine to the configured NAT Network through its VirtualBox network adapter.
Verified that the adapter was enabled and attached to the intended virtual network.

Step 6: Open the Kali LInux
Now, open the ready-to-use Kali linux and perform your activities.
