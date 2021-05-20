---
title: Bibliotekos SharePoint su tinklo disku
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 4b8245c3-a179-4524-ae83-0c22d539c202
ms.openlocfilehash: 6b7cb38362baa26bd39fe7478ef6dd1971b5b063
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52542829"
---
# <a name="map-a-sharepoint-library-to-a-network-drive"></a><span data-ttu-id="a9741-102">Bibliotekos SharePoint su tinklo disku</span><span class="sxs-lookup"><span data-stu-id="a9741-102">Map a SharePoint library to a network drive</span></span>

<span data-ttu-id="a9741-103">Užuot susieę tinklo diską, sinchronizuokite SharePoint su naujuoju "OneDrive" sinchronizavimo klientu, kuris teikia failus pagal poreikį.</span><span class="sxs-lookup"><span data-stu-id="a9741-103">Instead of mapping a network drive, sync SharePoint files with the new OneDrive sync client, which provides Files On-Demand.</span></span> <span data-ttu-id="a9741-104">Pasiekite visus savo failus "OneDrive" nenaudodami vietinės saugyklos vietos.</span><span class="sxs-lookup"><span data-stu-id="a9741-104">Access all your files in OneDrive without using local storage space.</span></span> <span data-ttu-id="a9741-105">Daugiau informacijos žr. [Failų sinchronizavimas SharePoint Teams](https://support.microsoft.com/office/sync-sharepoint-and-teams-files-with-your-computer-6de9ede8-5b6e-4503-80b2-6190f3354a88) su kompiuteriu ir Disko vietos įrašymas naudojant [""OneDrive""](https://support.microsoft.com/office/save-disk-space-with-onedrive-files-on-demand-for-windows-10-0e6860d3-d9f3-4971-b321-7092438fb38e)pagal poreikį Windows 10 .</span><span class="sxs-lookup"><span data-stu-id="a9741-105">For more information, see [Sync SharePoint and Teams files with your computer](https://support.microsoft.com/office/sync-sharepoint-and-teams-files-with-your-computer-6de9ede8-5b6e-4503-80b2-6190f3354a88) and [Save disk space with OneDrive Files On-Demand for Windows 10](https://support.microsoft.com/office/save-disk-space-with-onedrive-files-on-demand-for-windows-10-0e6860d3-d9f3-4971-b321-7092438fb38e).</span></span>

<span data-ttu-id="a9741-106">Jei pasirinksite susieti diską, o ne naują [""OneDrive"" sinchronizavimo klientą,](https://support.microsoft.com/office/sync-sharepoint-and-teams-files-with-your-computer-6de9ede8-5b6e-4503-80b2-6190f3354a88)įsitikinkite, kad atlikite šiuos veiksmus:</span><span class="sxs-lookup"><span data-stu-id="a9741-106">If you choose to map a drive instead of using [the new OneDrive sync client](https://support.microsoft.com/office/sync-sharepoint-and-teams-files-with-your-computer-6de9ede8-5b6e-4503-80b2-6190f3354a88), make sure you follow these steps:</span></span>

- [<span data-ttu-id="a9741-107">Susietų tinklo diskų, kurie jungiasi prie "SharePoint Online" trikčių diagnostika</span><span class="sxs-lookup"><span data-stu-id="a9741-107">Troubleshoot mapped network drives that connect to SharePoint Online</span></span>](/sharepoint/support/administration/troubleshoot-mapped-network-drives)

- [<span data-ttu-id="a9741-108">Autentifikavimo klaidos įvyksta, kai klientas nepalaiko TLS 1.2</span><span class="sxs-lookup"><span data-stu-id="a9741-108">Authentication errors occur when client doesn't have TLS 1.2 support</span></span>](/sharepoint/troubleshoot/administration/authentication-errors-tls12-support#network-drive-mapped-to-a-sharepoint-library)  

<span data-ttu-id="a9741-109">**PASTABA:** Jei naudojate "Internet Explorer 10" su ""Windows 8"" arba "Windows 7" ir gaunate  **"Access"** atmestas arba Kelias nepasiekiamas susiedami diską, išspręskite šią problemą diegdami šias karštąsias [pataisas.](https://support.microsoft.com/topic/error-when-you-open-a-sharepoint-document-library-in-windows-explorer-or-map-a-network-drive-to-the-library-after-you-install-internet-explorer-10-96e640ba-059f-9b09-bb91-2a0319ee8b1d)</span><span class="sxs-lookup"><span data-stu-id="a9741-109">**NOTE:** If you use Internet Explorer 10 with Windows 8 or Windows 7, and receive **Access denied** or **Path is not accessible** when mapping a drive, resolve this problem by installing this [hotfix](https://support.microsoft.com/topic/error-when-you-open-a-sharepoint-document-library-in-windows-explorer-or-map-a-network-drive-to-the-library-after-you-install-internet-explorer-10-96e640ba-059f-9b09-bb91-2a0319ee8b1d).</span></span>