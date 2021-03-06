<properties
	pageTitle="Create a custom virtual machine in Azure"
	description="Learn how to create a custom virtual machine in Azure."
	services="virtual-machines"
	documentationCenter=""
	authors="KBDAzure"
	manager="timlt"
	editor="tysonn"/>

<tags
	ms.service="virtual-machines"
	ms.workload="infrastructure-services"
	ms.tgt_pltfrm="na"
	ms.devlang="na"
	ms.topic="get-started-article" 
	ms.date="07/21/2015"
	ms.author="kathydav"/>

#How to Create a Custom Virtual Machine

A *custom* virtual machine simply means a virtual machine you create using the **From Gallery** option because it gives you more configuration choices than the **Quick Create** option. These choices include:

- Connecting the VM to a virtual network
- Installing the VM Agent and extensions, such as for antimalware
- Adding the VM to an existing cloud service
- Adding the VM to an existing storage account
- Adding the VM to an availability set

**Important**: If you want your virtual machine to use a virtual network so you can connect to it directly by hostname or set up cross-premises connections, make sure you specify the virtual network when you create the virtual machine. A virtual machine can be configured to join a virtual network only when you create the virtual machine. For details on virtual networks, see [Azure Virtual Network Overview](http://go.microsoft.com/fwlink/p/?LinkID=294063).

[AZURE.INCLUDE [virtual-machines-create-WindowsVM](../../includes/virtual-machines-create-WindowsVM.md)]
 