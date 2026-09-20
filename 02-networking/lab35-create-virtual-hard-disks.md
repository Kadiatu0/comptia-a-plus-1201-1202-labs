# Lab 35 – Create Virtual Hard Disks

## Scenario

In this lab, I used Hyper-V Manager to create two new virtual machines for future Windows 11 testing. I configured the virtual machines with specific memory, networking, and virtual hard disk settings and configured dynamic memory for VM2.

---

## Objectives

- Create a new virtual machine named VM1.
- Create a new virtual machine named VM2.
- Configure virtual machine generations.
- Configure startup memory.
- Configure dynamic memory for VM2.
- Configure network connections.
- Create and configure virtual hard disks.
- Configure minimum and maximum RAM values for VM2.

---

## Technologies

- Hyper-V
- Hyper-V Manager
- Virtual Machines
- Virtual Hard Disks
- VHDX
- Dynamic Memory
- Generation 1 Virtual Machines
- External Networking
- Internal Networking
- Windows 11 Virtualization

---

## Skills Demonstrated

- Virtual Machine Creation
- Hyper-V Manager Usage
- Virtual Hard Disk Configuration
- VHDX Configuration
- Virtual Machine Memory Configuration
- Dynamic Memory Configuration
- Virtual Network Configuration
- VM Storage Configuration
- Hyper-V Virtualization Management

---

## Procedure

1. Opened **Hyper-V Manager** from the Start menu.
2. Right-clicked **ITADMIN** and selected **New > Virtual Machine**.

3. Created **VM1** with the following configuration:
   - Virtual machine name: **VM1**
   - Virtual machine location: **D:\HYPERV**
   - Generation: **Generation 1**
   - Startup memory: **1024 MB**
   - Dynamic Memory: **Disabled**
   - Network connection: **External**
   - Virtual hard disk name: **VM1.vhdx**
   - Virtual hard disk location: **D:\HYPERV\Virtual Hard Disks**
   - Virtual hard disk size: **50 GB**
   - Operating system: **Install an operating system later**
4. Selected **Finish** to create VM1.

5. Created **VM2** with the following configuration:
   - Virtual machine name: **VM2**
   - Virtual machine location: **D:\HYPERV**
   - Generation: **Generation 1**
   - Startup memory: **2048 MB**
   - Dynamic Memory: **Enabled**
   - Network connection: **Internal**
   - Virtual hard disk name: **VM2.vhdx**
   - Virtual hard disk location: **D:\HYPERV\Virtual Hard Disks**
   - Virtual hard disk size: **250 GB**
   - Operating system: **Install an operating system later**
6. Selected **Finish** to create VM2.

7. Opened the settings for **VM2**.
8. Selected **Memory**.
9. Configured the dynamic memory settings:
   - Minimum RAM: **512 MB**
   - Maximum RAM: **4096 MB**
10. Selected **OK** to save the VM2 memory configuration.
11. Verified that both virtual machines were created with the required virtual hard disk, memory, and networking settings.

---

## Outcome

Successfully created VM1 and VM2 in Hyper-V Manager with the required virtual hard disks, memory, and network configurations. VM1 was configured with 1024 MB of static memory and an external network connection, while VM2 was configured with 2048 MB of startup memory, dynamic memory, an internal network connection, and adjustable RAM from 512 MB to 4096 MB.

---

## Key Takeaways

- Learned how to create virtual machines using Hyper-V Manager.
- Practiced configuring Generation 1 virtual machines.
- Learned how to create dynamically expanding VHDX files.
- Practiced configuring virtual hard disk size and storage locations.
- Learned the difference between external and internal virtual networking.
- Practiced configuring startup memory for virtual machines.
- Learned how dynamic memory allows Hyper-V to adjust a VM's available RAM.
- Practiced setting minimum and maximum RAM limits for a virtual machine.