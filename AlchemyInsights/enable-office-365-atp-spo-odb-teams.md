---
title: Įgalinti "Office 365" ATP SharePoint, "OneDrive" ir "Microsoft" komandos
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: ae2f574663ae3233a056589c2d5a578171f3b2f4
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 04/23/2019
ms.locfileid: "32403041"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a><span data-ttu-id="97d26-102">Įjungti Office 365 Išplėstinė grėsmę apsaugos SharePoint internete, "OneDrive" ir "Microsoft" komandos</span><span class="sxs-lookup"><span data-stu-id="97d26-102">Enable Office 365 Advanced Threat Protection for SharePoint Online, OneDrive, and Microsoft Teams</span></span>

1. <span data-ttu-id="97d26-103">Eikite į https://protection.office.com ir prisijunkite.</span><span class="sxs-lookup"><span data-stu-id="97d26-103">Go to https://protection.office.com and sign in.</span></span>
2. <span data-ttu-id="97d26-104">Pasirinkti **grėsmės valdymo** > **politikos** > **Saugos priedus**.</span><span class="sxs-lookup"><span data-stu-id="97d26-104">Choose **Threat management** > **Policy** > **Safe Attachments**.</span></span>
3. <span data-ttu-id="97d26-105">Pasirinkite **įjungti ATP SharePoint, "OneDrive", ir "Microsoft" komandomis**, o tada spustelėkite **įrašyti**.</span><span class="sxs-lookup"><span data-stu-id="97d26-105">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**, and then click **Save**.</span></span>
4. <span data-ttu-id="97d26-106">(Rekomenduojama) Kaip visuotinis administratorius arba SharePoint Online administratorius, paleiskite [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet **DisallowInfectedFileDownload** parametras nustatytas kaip *true*.</span><span class="sxs-lookup"><span data-stu-id="97d26-106">(Recommended) As a global administrator or a SharePoint Online administrator, run the [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet with the **DisallowInfectedFileDownload** parameter set to *true*.</span></span>
5. <span data-ttu-id="97d26-107">(Rekomenduojama) [Nustatyti įspėjimus](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) aptikti failai.</span><span class="sxs-lookup"><span data-stu-id="97d26-107">(Recommended) [Set up alerts](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) for detected files.</span></span>

> [!NOTE]
> <span data-ttu-id="97d26-108">ATP bus NTT nuskaityti kiekvieną vieną failą į SharePoint Online, OneDrive arba "Microsoft" Teams.</span><span class="sxs-lookup"><span data-stu-id="97d26-108">ATP will nto scan every single file in SharePoint Online, OneDrive, or Microsoft Teams.</span></span> <span data-ttu-id="97d26-109">Failai yra nuskaitomi asynchronicznie, per procesą, kuris naudoja pasidalijimo ir svečių aktyvumas renginiai, kartu su protingas Euristika ir pavojaus signalus kenkėjiškų failų.</span><span class="sxs-lookup"><span data-stu-id="97d26-109">Files are scanned asynchronously, through a process that uses sharing and guest activity events, along with smart heuristics and threat signals to identify malicious files.</span></span> <span data-ttu-id="97d26-110">Matyti [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="97d26-110">See [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>