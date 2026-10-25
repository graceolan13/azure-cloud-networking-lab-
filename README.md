# Azure Cloud Networking Lab

## Overview

This project documents a hands-on cloud networking lab completed using Microsoft Azure for my Data and Network Communications coursework at Howard University. The lab involved creating a virtual network, configuring public and private subnets, setting up network security rules, and deploying an Ubuntu virtual machine.

## Lab Breakdown

1. Setting up the virtual network 

- Created a resource group to keep my Azure resources organized.

- Set up a virtual network to connect resources within Azure.

2. Creating Subnets 

- Created public and private subnets to organize the network into smaller sections.

- Assigned IP address ranges to each subnet.

3. Network Security

- Created a Network Security Group (NSG) to control network traffic.

- Set up a rule to allow SSH connections from my IP address.

- Added a rule to allow HTTP traffic.

- Connected the NSG to the public subnet.

4. Virtual Machine Deployment

- Set up an Ubuntu virtual machine in the public subnet.

- Checked the VM's network settings and the overall network layout.

### Key Takeaways

Learned how virtual networks and subnets work together.

Practiced controlling incoming traffic with security rules.

Got hands-on experience setting up a virtual machine in Azure.
