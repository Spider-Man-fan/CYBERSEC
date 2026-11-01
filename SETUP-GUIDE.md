# CYBER-V VMware Setup Guide

## Overview
**CYBER-V** is a VMware virtual machine configuration for educational cybersecurity practice.

**Use only on systems you own or have permission to test. Do not use for malware or illegal activity.**

## Requirements
- VMware Workstation, VMware Player, or VMware Fusion
- A Linux ISO (recommended: Kali Linux or Ubuntu)

## How to Use

1. Download `CYBER-V.vmx` and place it in a folder (e.g. `C:\VMs\CYBER-V\`).
2. Open VMware.
3. Go to **File → Open** and select `CYBER-V.vmx`.
4. When asked, select **"I copied it"**.
5. Edit the virtual machine settings:
   - Attach your Linux ISO to the CD/DVD drive.
   - Optionally increase RAM or CPU if your host allows.
6. Power on the VM and install the operating system.
7. After installation, take a snapshot named "Clean Install".

## Default Specs
- 2 CPUs
- 4 GB RAM
- Host-Only network (isolated)
- 40 GB virtual disk (created on first boot)

## Tips
- Use Host-Only or NAT networking for safety.
- Take snapshots before testing anything.
- Never connect this VM directly to the internet without proper controls if doing security research.

This configuration is provided for educational purposes only.
