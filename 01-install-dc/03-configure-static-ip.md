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

3. In the **Network Connections**, right-click **Ethernet**, and select **Properties**

![Network](https://raw.githubusercontent.com/ProJensen/Active-Directory-Lab/refs/heads/main/01-install-dc/screencap/02-conf-ip/2-Properties.png)

4. Select **Internet Protocol Version 4 (IPv4)** → **Properties**

![IPv4](https://raw.githubusercontent.com/ProJensen/Active-Directory-Lab/refs/heads/main/01-install-dc/screencap/02-conf-ip/2-IPv4%20Properties.png)

5. Set the **IP address** and the **DNS server address**


6. Click **OK**
