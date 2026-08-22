# Lab 29 – Configure IP Addresses

## Scenario

As an IT administrator, I configured the Executive Office workstation with static IPv4 settings on two network interface cards and verified network connectivity.

---

## Objectives

- Configure IPv4 settings for the Ethernet NIC.
- Configure IPv4 settings for the Ethernet 2 NIC.
- Configure the correct subnet masks and default gateway.
- Configure preferred and alternate DNS servers.
- Verify network connectivity using `ping`.

---

## Technologies

- IPv4
- TCP/IP
- Ethernet
- Subnet Masks
- Default Gateway
- DNS
- Static IP Addressing
- PowerShell / Terminal
- Ping

---

## Skills Demonstrated

- IPv4 Configuration
- Static IP Address Assignment
- Subnet Mask Configuration
- Default Gateway Configuration
- DNS Configuration
- Multiple NIC Configuration
- Network Troubleshooting
- Network Connectivity Testing
- PowerShell Command-Line Usage

---

## Procedure

1. Opened **Settings** and selected **Network & internet**.
2. Selected the **Ethernet** network adapter.
3. Changed IP assignment to **Manual** and enabled IPv4.
4. Configured Ethernet with:
   - IP address: **192.168.0.254**
   - Subnet mask: **255.255.255.0**
   - Default gateway: **192.168.0.5**
   - Preferred DNS: **163.128.78.93**
   - Alternate DNS: **163.128.80.93**
5. Saved the Ethernet configuration.
6. Opened **Advanced network settings** and selected **More network adapter options**.
7. Opened the properties for **Ethernet 2**.
8. Configured Ethernet 2 with:
   - IP address: **10.0.255.254**
   - Subnet mask: **255.255.0.0**
   - Default gateway: **Blank**
   - Preferred DNS: **Blank**
9. Saved and closed the Ethernet 2 configuration.
10. Opened **Terminal (Admin)**.
11. Used the following command to test connectivity to the preferred DNS server:

```powershell
ping 163.128.78.93