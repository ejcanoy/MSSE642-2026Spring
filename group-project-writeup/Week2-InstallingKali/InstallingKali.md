# Installing Kali 

## MSSE642 Assignment 1: Pen Testing Lab Setup
**Student Name:** Euan Canoy
**Date:** January 30, 2026

## Project Overview
The goal of this assignment is to establish a local penetration testing environment consisting of a Kali Linux attack machine and a Metasploitable2 target machine. Due to using a Mac with Apple Silicon, I have utilized **VMware Fusion** and **UTM** as virtualization alternatives to Oracle VirtualBox to ensure a functional and isolated host-only network.

---

### Screenshot 1: VMware Fusion Library
![VmWare Fusion virtual machine screenshot](<Screenshot 2026-01-30 at 4.18.44 PM.png>)
**Description:** This screenshot shows the VMware Fusion library interface with the Kali Linux virtual machine installed, serving as the alternative to the Vagrant status list.

---

### Screenshot 2: UTM Virtual Machine Library + Environment Configuration (UTM)
![UTM virtual machine screenshot](<Screenshot 2026-01-30 at 4.15.13 PM.png>)
**Description:** This confirms the use of UTM for the Metasploitable2 instance, fulfilling the virtualization software proof requirement.

Verification of the VM configuration within UTM, showing the **1GB RAM** allocation and the **Host-Only** network adapter setup required for lab connectivity.

---

### Screenshot 3: Kali Linux Login and IP Verification
![kali linux screenshot](<Screenshot 2026-01-30 at 4.09.24 PM.png>)
**Description:** A terminal session inside Kali Linux showing a successful login. The output of the `ifconfig` command verifies the active IP address for the virtual network.

---

### Screenshot 4: Logged into Metasploitable2
![metasploitable screenshot](<Screenshot 2026-01-30 at 4.11.24 PM.png>)
**Description:** Confirmation of successful login to the Metasploitable2 target machine using the default `msfadmin` credentials.