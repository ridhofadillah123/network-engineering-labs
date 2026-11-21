# RT/RW Network Infrastructure

## Project Overview

RT/RW Network Infrastructure is a small-scale network infrastructure simulation designed to represent how a residential neighborhood network operates.

This project demonstrates how network devices communicate with each other, how network segmentation is implemented, and how access to specific network resources, such as CCTV systems, can be controlled.

The project is developed using Cisco Packet Tracer as my first portfolio project in the field of Network Engineering. Its main purpose is to build a practical understanding of network infrastructure commonly found in everyday environments, particularly in residential areas.

## Project Objectives

- Understand the basic architecture of a residential network infrastructure.
- Learn how network devices communicate within a network.
- Implement network segmentation using VLANs.
- Configure communication between different VLANs.
- Implement DHCP for automatic IP address assignment.
- Configure network security using Access Control Lists (ACL).
- Control and restrict access to CCTV devices based on network policies.
- Develop practical skills in network configuration and troubleshooting.

## Network Devices

The network infrastructure consists of the following devices:

- Router: Connects the internal network to an external network or ISP.
- Multilayer Switch: Handles VLANs, inter-VLAN routing, and network traffic management.
- Access Switch: Connects end devices to the network.
- Wireless Access Point: Provides wireless connectivity for supported devices.
- PC and Laptop: Represent residential users, administrators, and security personnel.
- CCTV Devices: Represent surveillance cameras connected to the network.

## Technologies & Implementations

The following technologies and configurations are implemented in this project:

- VLAN (Virtual LAN): Separates network segments based on their functions.
- Trunking: Enables multiple VLANs to communicate across switch connections.
- DHCP (Dynamic Host Configuration Protocol): Automatically assigns IP addresses to network devices.
- Inter-VLAN Routing: Enables communication between different VLANs through a multilayer switch.
- Extended ACL (Access Control List): Controls network traffic based on source and destination IP addresses.
- IP Addressing: Implements subnetting and IP address allocation for each network segment.
- Network Troubleshooting: Tests connectivity and verifies network configurations.

## Network Security

One of the main implementations in this project is CCTV access control.

The network is configured so that authorized security personnel can access CCTV devices, while residential users are restricted from accessing them.

This is implemented using Extended Access Control Lists (ACL) to control traffic between network segments.

## Tools Used

- Cisco Packet Tracer
- Cisco IOS Command Line Interface (CLI)

## Project Status

Current Status: Network configuration and CCTV access control implementation.

The project includes network segmentation, DHCP configuration, trunking, inter-VLAN routing, and ACL implementation.

Documentation, connectivity testing, and configuration evidence are being organized as part of the project portfolio.

## Author

Personal Network Engineering Portfolio Project.