# Lab 37 – Manage IaaS Virtual Machines in Azure

## Scenario

You are the network administrator for your company. As part of configuring Azure, you need to create a virtual server in Azure. The virtual machine will run Windows Server 2022 and use the existing `CorpNetCloud` resource group.

## Objectives

- Create an Azure virtual machine.
- Configure the subscription and resource group.
- Configure the virtual machine name, region, image, and size.
- Create an administrator account.
- Configure the OS disk.
- Configure network connectivity.
- Review and deploy the virtual machine.

## Technologies

- Microsoft Azure
- Azure Virtual Machines
- Windows Server 2022
- Standard HDD
- Virtual Networking
- Google Chrome

## Skills Demonstrated

- Creating Azure virtual machines
- Configuring Azure VM resources
- Configuring administrator accounts
- Configuring virtual machine disks
- Configuring virtual networking
- Reviewing and deploying Azure resources

## Procedure

1. Open Google Chrome and access the Azure portal.
2. Under Azure Services, select **Virtual machines**.
3. Select **Create > Azure virtual machine**.
4. Configure the project details:
   - Subscription: `CorpNet Production`
   - Resource group: `CorpNetCloud`
5. Configure the instance details:
   - Virtual machine name: `CorpCloud1`
   - Region: `(US) West US2`
   - Image: `Windows Server 2022 Datacenter: Azure Edition - Gen2`
   - Size: `Standard_D4s_v3 - 4 vcpu, 16 GiB memory`
6. Configure the administrator account:
   - Username: `CorpAdmin`
   - Password: `corpP@ssw0rd`
7. Select **Next: Disks**.
8. Configure the OS disk:
   - OS disk type: `Standard HDD`
   - Delete with VM: Selected
9. Select **Next: Networking**.
10. Verify the network settings:
    - Virtual network: `(new) CorpNetCloud-vnet`
    - Subnet: `(new) default (10.0.0.0)/24`
    - Public IP: `(new) CorpCloud1-ip`
11. Select **Review + create**.
12. Review the virtual machine configuration.
13. Select **Create**.
14. Monitor the deployment until it is complete.
15. Select **Go to resource** and verify that the virtual machine was created.

## Outcome

Successfully configured and deployed the `CorpCloud1` Azure virtual machine using the required Windows Server 2022 image, Standard HDD storage, administrator account, and default Azure network configuration.

## Key Takeaways

- Learned how to create an Azure IaaS virtual machine.
- Practiced configuring VM compute and storage settings.
- Learned how to configure an administrator account.
- Practiced configuring Azure virtual networking.
- Learned how to review and deploy an Azure virtual machine.