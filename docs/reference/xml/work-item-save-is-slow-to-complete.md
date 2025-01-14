---
title: Work item save is slow to complete
titleSuffix: TFS
description: Occurs when you save a work item.
ms.technology: devops-agile
ms.custom: process
ms.assetid: 367d2f3d-8dcd-4311-a411-7ba93217aabf
ms.author: kaelli
author: KathrynEE
ms.topic: troubleshooting
monikerRange: 'tfs-2013'
ms.date: 01/20/2017
---

# Work item save is slow to complete

[!INCLUDE [version-eq-2013](../../includes/version-eq-2013.md)]

This problem might occur when you save a work item. The problem might be intermittent and difficult to reproduce.  
  
 **Possible Causes**  
  
 The client computer might not be configured to automatically detect the link speed of its network adapter. This setting might decrease performance between the client computer and Team Foundation Server.  
  
 **Solutions**  
  
 On the client computer, enable automatic detection of the link speed for the network adapter. For more information, see [Configure a network adapter to automatically adjust speed](configure-network-adapter-automatically-adjust-speed.md).