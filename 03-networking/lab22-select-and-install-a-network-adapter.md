# Lab 22 – Select and Install a Network Adapter

## Scenario

As an IT administrator, I was tasked with upgrading the Executive Office workstation's network connection to provide faster network speeds.

---

## Objectives

- Install the fastest available network adapter.
- Connect the workstation to the network using the new NIC.
- Verify local and internet connectivity.

---

## Technologies

- PCIe Network Interface Card (NIC)
- 1000BaseTX Ethernet
- Ethernet Cable
- PowerShell
- Ping

---

## Skills Demonstrated

- NIC Installation
- Network Hardware Configuration
- Ethernet Connectivity
- Network Troubleshooting

---

## Procedure

1. Installed a **10/100/1000BaseTX PCIe network adapter** into an available PCIe slot.
2. Moved the Ethernet cable from the built-in network port to the new NIC.
3. Powered on the workstation and waited for Windows to load.
4. Opened Terminal as Administrator.
5. Tested local network connectivity using:
   - `ping 192.168.0.10`
6. Tested internet connectivity using:
   - `ping 198.28.2.254`
7. Verified successful network communication.

---

## Outcome

Successfully upgraded the Executive workstation to a 1000BaseTX network connection and verified connectivity to both the local network and internet.

---

## Key Takeaways

- Learned how to select a NIC based on network speed requirements.
- Practiced installing a PCIe network adapter.
- Used `ping` to verify network connectivity.