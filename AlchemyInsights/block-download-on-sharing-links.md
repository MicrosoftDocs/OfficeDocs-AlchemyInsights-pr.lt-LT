---
title: Blokuoti atsisiuntimą bendrinant saitus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000213"
- "5715"
ms.openlocfilehash: 8cb53754125cedf4a3d0426d6c3bf70297eb3d74
ms.sourcegitcommit: c46b8df485edbd13e8bb4d1b2ba1c2821ddc9da0
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 05/23/2020
ms.locfileid: "44358038"
---
# <a name="block-download-on-sharing-links"></a><span data-ttu-id="4178a-102">Blokuoti atsisiuntimą bendrinant saitus</span><span class="sxs-lookup"><span data-stu-id="4178a-102">Block download on sharing links</span></span>

<span data-ttu-id="4178a-103">**Blokuoti atsisiuntimą** galima **tik peržiūrėti saitus** su "Office" dokumentais.</span><span class="sxs-lookup"><span data-stu-id="4178a-103">**Block download** is available for **view-only links** to Office documents.</span></span> <span data-ttu-id="4178a-104">Pasirinkus šią parinktį, žmonės, kurie gauna prieigą prie failo per sukurtą saitą, nematys failo atsisiuntimo, spausdinimo ar kopijavimo parinkčių.</span><span class="sxs-lookup"><span data-stu-id="4178a-104">When you select this option, people who gain access to the file via the link you created will not see options to download, print, or copy the file.</span></span>

<span data-ttu-id="4178a-105">Administratoriai gali kontroliuoti, ar parametras "blokuoti atsisiuntimą" rodomas tik "Office" failams, ar ne, pakeisdami `BlockDownloadLinksFileType` [set-SPOTenant arba Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-spotenant?view=sharepoint-ps) "PowerShell" cmdlet parametrą. [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps)</span><span class="sxs-lookup"><span data-stu-id="4178a-105">Administrators can control whether the "block download" setting appears only for Office files or not by changing the `BlockDownloadLinksFileType` setting in the [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/set-spotenant?view=sharepoint-ps) or [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) PowerShell cmdlets.</span></span>