## IP Address Configuration

Configure the **Host-Only network adapter** with the following settings:

| Setting | Value |
|------|------|
| IP Address | `192.168.0.10` |
| Subnet Mask | `255.255.255.0` |
| Default Gateway | `192.168.0.1` |
| Preferred DNS Server | `127.0.0.1` |

## Configuration Steps

1. In the **Server Manager Page**, click **Local Server**
2. In the **Local Server** tab, under "PROPERTIES", click **Ethernet: IPv4 address assigned by DHCP, IPv6 enabled**

![Ethernet](https://raw.githubusercontent.com/ProJensen/Active-Directory-Lab/refs/heads/main/01-install-dc/screencap/02-conf-ip/2-Click%20Ethernet.png)
3. Select **More network adapter options**
4. Right-click **Ethernet (Host-Only Adapter)** → **Properties**
5. Select **Internet Protocol Version 4 (IPv4)** → **Properties**
6. Select **Use the following IP address**
7. Enter the values listed above
8. Click **OK** and close all dialogs
