# Lumina-University-Network-Project
HND Final Project – Network Design &amp; Implementation of Lumina University

📘 Lumina University – Network Design & Implementation Project
HND Final Project – Network Engineering

This repository contains the complete documentation, configurations, diagrams, and cloud deployment steps for the Lumina University Network Project, designed as part of our Higher National Diploma in Network Engineering.

🔎 Project Overview

The goal of this project is to design and implement a secure, scalable, and highly available network infrastructure suitable for a modern university environment.

The network spans 5 floors, including:

Classrooms

Labs

Administrative offices

Server rooms

Library

CCTV control room

It includes advanced security, virtualization, cloud hosting, and monitoring features.

🏗 Key Technologies Used
🔐 Security & Core Networking

pfSense Firewall

VLAN segmentation

DHCP

DNS

OpenVPN remote access

Firewall rule sets

Dual WAN design (primary + backup ISP)

🌐 Switching

Cisco Catalyst 9300 (L3 Core)

Cisco Catalyst 2960 & 9200 (L2)

STP, EtherChannel, trunking, access VLANs

🖥 Virtualization

VMware ESXi Hosts

vCenter Appliance

Veeam Backup & Replication

Disaster Recovery (DR) site

☁️ Cloud Deployment

AWS EC2

Hosting university LMS web page

🗄 Storage

Synology NAS

iSCSI storage

LUN mapping

📊 Monitoring

Zabbix Server

Switch monitoring

Alerts & graphing

📄 Included in This Repository
📁 Final-Project-Report.pdf  
📁 Configurations/
📁 AWS/
📁 Network-Diagram/
📁 Screenshots/
📁 Budget-Table/
📁 IP-Table/

🖥 Network Architecture
Components:

Core Network: pfSense

Two L3 switches (redundancy)

Multiple L2 access switches

Wi-Fi networks with VLAN separation

CCTV isolated VLAN

Virtual Server Farm (ESXi, vCenter)

🔧 Main Implementations

VLAN creation & DHCP scopes

Inter-VLAN routing

Access control lists (ACLs)

High-availability suggestions

Virtual machines deployment

NAS storage integration

EC2 web server hosting

🧩 Project Goals Achieved

✔ High availability
✔ Redundant switching
✔ Segmented secure network
✔ Cloud-based LMS
✔ Full monitoring through Zabbix
✔ DR site with replication
✔ Comprehensive documentation

📌 Future Enhancements

pfSense HA (CARP)

10G backbone uplinks

Separate SSIDs for staff/students/guests

SIEM and IDS/IPS integrations

More cloud migration
