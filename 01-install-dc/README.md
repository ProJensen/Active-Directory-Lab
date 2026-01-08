## Lab 01 - Install Domain Controller

1. [Create VirtualBox VM](01-create-vm-virtualbox.md)

2. [Install Windows Server 2025](02-install-windows-server-2025.md)

3. [Configure Static IP](03-configure-static-ip.md)

4. [Rename Server to DC1](04-rename-server.md)

5. [Install AD DS Role](05-install-ad-ds-role.md)

6. [Promote Domain Controller](06-promote-domain-controller.md)


1. Create a new VM in VirtualBox.

2. Attach Windows Server 2025 ISO
     #### Domain Controller (Windows Server 2025)
    - CPU: 2 cores
    - Memory: 4 GB
    - Disk: 50 GB
    
    Network Adapters:
    - Adapter 1: Custom NAT Network (setup in preferences :arrow_right: Network :arrow_right: Add new NAT Network :arrow_right: make your own Network Name, and Network CIDR)
![NAT Network](https://raw.githubusercontent.com/ProJensen/Active-Directory-Lab/refs/heads/main/01-install-dc/screencap/0-Setup%20NAT%20Networks.png)

3. [Start the VM and complete the OS installation](Install-Win-Server-in-VB.md)

