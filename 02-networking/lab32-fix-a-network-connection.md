# Lab 32 – Fix a Network Connection

## Scenario

As the IT administrator for a small corporate network, I was tasked with troubleshooting the Office1 computer after the user reported that it could no longer access the network or internet. I reviewed the computer's network configuration and hardware to identify and correct the connection problems.

---

## Objectives

- Diagnose network connectivity problems on the Office1 computer.
- Review the computer's network configuration.
- Verify the IP address and subnet mask.
- Identify incorrect operating system or hardware settings.
- Correct the network configuration.
- Verify connectivity to the Office2 computer.
- Verify connectivity to the DNS server.

---

## Technologies

- IPv4
- TCP/IP
- Ethernet
- IP Addressing
- Subnet Mask
- DNS
- Network & Internet Settings
- `ipconfig`
- Ping
- Network Troubleshooting

---

## Skills Demonstrated

- Network Troubleshooting
- IPv4 Configuration
- IP Address Verification
- Subnet Mask Configuration
- Ethernet Troubleshooting
- Network Adapter Troubleshooting
- DNS Connectivity Testing
- Command-Line Networking
- `ipconfig` Usage
- `ping` Usage
- Basic Network Diagnostics

---

## Procedure

1. Reviewed the network requirements and troubleshooting information.
2. Verified that the network does not use a DHCP server and that computers require static IP addresses.
3. Opened the **Settings** app on the Office1 computer.
4. Navigated to **Network & internet** and reviewed the Ethernet connection.
5. Reviewed the network adapter's IPv4 configuration.
6. Used the `ipconfig` command to examine the current network configuration.
7. Compared the Office1 network configuration with the required settings from the lab exhibit.
8. Checked the IP address to ensure it did not conflict with server addresses below **.15** or workstation addresses between **.30 and .34**.
9. Verified that the correct default subnet mask was configured.
10. Reviewed the physical network connection and verified that the Ethernet hardware was properly connected.
11. Corrected the identified network configuration and hardware problems.
12. Saved the corrected network settings.
13. Used `ipconfig` again to verify the updated network configuration.
14. Used the `ping` command to test connectivity to the Office2 computer.
15. Used the `ping` command to test connectivity to the DNS server.
16. Verified successful network communication.

---

## Outcome

Successfully diagnosed and corrected the network connection problems on the Office1 computer. After correcting the configuration and hardware issues, the computer was able to communicate with the Office2 computer and the DNS server.

---

## Key Takeaways

- Learned how to troubleshoot a network without a DHCP server.
- Practiced identifying incorrect static IP configurations.
- Learned how to verify network settings using `ipconfig`.
- Practiced checking the default subnet mask.
- Learned that network problems can be caused by both software and hardware.
- Practiced using `ping` to verify network connectivity.
- Learned how to troubleshoot multiple network problems on a workstation.