---
title: Atidaryti naudojant "Internet Explorer" neveikia
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: 73d33e50449345c312abdd39afcc36e0c95fd1c4
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 04/23/2019
ms.locfileid: "32419880"
---
# <a name="open-with-explorer-isnt-working"></a><span data-ttu-id="f4e43-102">Atidaryti naudojant "Internet Explorer" neveikia</span><span class="sxs-lookup"><span data-stu-id="f4e43-102">Open with Explorer isn't working</span></span>

<span data-ttu-id="f4e43-103">Jei nepavyksta **Atidaryti naudojant "Internet Explorer"** arba **failų naršyklės rodinį** įsitikinkite, WebClient tarnyboje yra nustatyta **veikia** pagal toliau nurodytus veiksmus.</span><span class="sxs-lookup"><span data-stu-id="f4e43-103">If **Open with Explorer** or **View in File Explorer** doesn't work make sure the WebClient service is set to **Running** by following the steps below.</span></span> <span data-ttu-id="f4e43-104">Pavyzdžiui, tai gali užtrukti ilgą laiką atidaryti biblioteką SharePoint arba "OneDrive", kai paslauga veikia.</span><span class="sxs-lookup"><span data-stu-id="f4e43-104">For example, it might take a long time to open a SharePoint or OneDrive library when the service is not running.</span></span> 
  
1. <span data-ttu-id="f4e43-105">"Windows" ieškos lauke, įveskite run, pasirinkite darbalaukio programą, vykdyti, įveskite services.msc ir pasirinkite **Enter**.</span><span class="sxs-lookup"><span data-stu-id="f4e43-105">In the Windows search box, type run, select the Run desktop app, type services.msc, and then select **Enter**.</span></span>
    
2. <span data-ttu-id="f4e43-106">Slinkite žemyn WebClient tarnybos ir patikrinkite stulpelį **Būsena** .</span><span class="sxs-lookup"><span data-stu-id="f4e43-106">Scroll down to the WebClient service and check the **Status** column.</span></span> <span data-ttu-id="f4e43-107">Jei WebClient tarnybos būsena nėra **veikia**, dukart spustelėkite tarnybos, spustelėkite **pradėti**ir tada spustelėkite **gerai**.</span><span class="sxs-lookup"><span data-stu-id="f4e43-107">If the WebClient service status is not **Running**, double-click the service, click **Start**, and then click **OK**.</span></span> <span data-ttu-id="f4e43-108">Įjungti paslaugą, jei reikia, pasirinkite **Rankinis** arba **Automatinis** lauke **Paleisties tipas** .</span><span class="sxs-lookup"><span data-stu-id="f4e43-108">Enable the service, if needed, by selecting either **Manual** or **Automatic** in the **Startup type** box.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="f4e43-109">Triktims atidaryti failų naršyklėje, ieškokite [atidaryti "Internet Explorer"](https://go.microsoft.com/fwlink/?linkid=871665).</span><span class="sxs-lookup"><span data-stu-id="f4e43-109">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span></span> <span data-ttu-id="f4e43-110">Ištirti sinchronizavimo kaip geresnė alternatyva: [sinchronizavimo SharePoint failai su nauja "OneDrive" sinchronizavimo klientas](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="f4e43-110">Explore sync as a better alternative: [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span> 
  

