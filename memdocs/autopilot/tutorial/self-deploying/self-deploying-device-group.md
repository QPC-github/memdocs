---
title: Windows Autopilot self-deploying mode - Step 4 of 6 - Create a device group
description: How to - Windows Autopilot self-deploying mode - Step 4 of 6 - Create a device group.
ms.prod: windows-client
ms.localizationpriority: medium
author: frankroj
ms.author: frankroj
ms.reviewer: jubaptis
manager: aaroncz
ms.date: 04/24/2023
ms.topic: tutorial
ms.collection: 
  - tier1
  - highpri
ms.technology: itpro-deploy
appliesto:
  - ✅ <a href="https://learn.microsoft.com/windows/release-health/supported-versions-windows-client" target="_blank">Windows 11</a>
  - ✅ <a href="https://learn.microsoft.com/windows/release-health/supported-versions-windows-client" target="_blank">Windows 10</a>
---

# Self-deploying mode: Create a device group

Autopilot self-deploying mode steps:
- Step 1: [Set up Windows automatic Intune enrollment](self-deploying-automatic-enrollment.md)
- Step 2: [Register devices as Autopilot devices](self-deploying-register-device.md)
> [!div class="checklist"]
> - **Step 3: Create a device group**
- Step 4: [Configure and assign Autopilot Enrollment Status Page (ESP)](self-deploying-esp.md)
- Step 5: [Create and assign Autopilot profile](self-deploying-autopilot-profile.md)

For an overview of the Windows Autopilot self-deploying mode workflow, see [Windows Autopilot self-deploying overview](self-deploying-workflow.md#workflow)

> [!NOTE]
>
> If you have already created device groups from another Autopilot scenario, you can skip this step and move on to [Step 4: Configure and assign Autopilot Enrollment Status Page (ESP)](self-deploying-esp.md). However, if you're deploying multiple different Autopilot scenarios to different devices, separate device groups are required for each Autopilot scenario.

## Create a device group

[!INCLUDE [How to create a device group in Intune](../includes/create-device-group.md)]

## Next step: Configure and assign the Enrollment Status Page (ESP)

> [!div class="nextstepaction"]
> [Step 4: Configure and assign Autopilot Enrollment Status Page (ESP)](self-deploying-esp.md)

## More information

[!INCLUDE [More information device group](../includes/more-info-device-group.md)]
