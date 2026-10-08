# Active Directory Homelab

## Overview

This project is a hands-on Active Directory lab built in VMware Workstation using Windows Server.

The goal of this lab is to gain practical experience with Windows Server administration, Active Directory, user and group management, domain environments, and basic troubleshooting.

## Environment

* Virtualization: VMware Workstation
* Server: Windows Server
* Domain Controller: DC01
* Active Directory Domain: taelab.local
* Role: Active Directory Domain Services (AD DS)
 
## Current Progress

* Created and configured a Windows Server VM using VMware Workstation
* Installed Windows Server and configured the server as `DC01`
* Installed Active Directory Domain Services (AD DS)
* Promoted `DC01` to a Domain Controller
* Created the `taelab.local` Active Directory domain and forest
* Configured a static IP address for DC01
* Created Organizational Units for IT, HR, and Users
* Created test domain users
* Created and configured security groups
* Added a test user to the Domain Admins group
* Created a Windows 11 client VM named `CLIENT01`
* Configured network connectivity between CLIENT01 and DC01
* Tested DNS/name resolution and connectivity to the domain
* Joined CLIENT01 to the `taelab.local` domain
* Organized CLIENT01 within the IT Organizational Unit
* Successfully logged into CLIENT01 using a domain account

## Skills Practiced

* Windows Server administration
* Active Directory Domain Services
* Domain Controllers
* Active Directory users and groups
* Organizational Units
* Security groups and permissions
* Domain administration
* DNS fundamentals
* Static IP configuration
* Windows 11 domain joining
* Basic network troubleshooting
* VMware virtualization
