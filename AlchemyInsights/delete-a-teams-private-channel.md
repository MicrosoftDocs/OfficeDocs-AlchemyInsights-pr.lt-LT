---
title: "\"Teams\" asmeninio kanalo ištrynimas"
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/24/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3781"
- "9001223"
ms.openlocfilehash: 2ee998f0c70973645c273a2a6609af2420a4f74b
ms.sourcegitcommit: b10cea11b4975354b91193327b58aa4740d34833
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 07/28/2020
ms.locfileid: "45439323"
---
# <a name="delete-a-teams-private-channel"></a><span data-ttu-id="1f3f7-102">"Teams" asmeninio kanalo ištrynimas</span><span class="sxs-lookup"><span data-stu-id="1f3f7-102">Delete a Teams private channel</span></span>

<span data-ttu-id="1f3f7-103">"Microsoft" žino apie problemą, naikinant "Teams" privatųjį kanalą, jei įgalinta "SharePoint" saugojimo strategijos, skirtos pagrindinei "SharePoint" svetainei.</span><span class="sxs-lookup"><span data-stu-id="1f3f7-103">Microsoft is aware of an issue deleting a Teams private channel if you have SharePoint Retention Policies enabled for the underlying SharePoint site.</span></span> <span data-ttu-id="1f3f7-104">"Microsoft" dirba su nustatyti.</span><span class="sxs-lookup"><span data-stu-id="1f3f7-104">Microsoft is working on a fix.</span></span> <span data-ttu-id="1f3f7-105">Tuo tarpu galite naudoti šiuos problemos sprendimus, kad panaikintumėte privatų kanalą.</span><span class="sxs-lookup"><span data-stu-id="1f3f7-105">In the meantime, you can use the following workarounds to delete the private channel.</span></span>

<span data-ttu-id="1f3f7-106">**Išskirkite komandos / svetainių rinkinį iš "Sharepoint" saugojimo strategijos.**</span><span class="sxs-lookup"><span data-stu-id="1f3f7-106">**Exclude the Team/site collection from the Sharepoint retention policy.**</span></span>

1. <span data-ttu-id="1f3f7-107">Eikite į "Office 365" administravimo portalą ir kairiojoje naršymo srityje pasirinkite **Rodyti viską.**</span><span class="sxs-lookup"><span data-stu-id="1f3f7-107">Go to the Office 365 admin portal, and select **Show all** in the left navigation pane.</span></span>
2. <span data-ttu-id="1f3f7-108">Dalyje **Administravimo centrai**eikite į **Saugos & atitikties**  >  **duomenų praradimo prevencijos**  >  **strategija**.</span><span class="sxs-lookup"><span data-stu-id="1f3f7-108">Under **Admin centers**, go to **Security & Compliance** > **Data Loss Prevention** > **Policy**.</span></span>
3. <span data-ttu-id="1f3f7-109">Nustatykite bet kokią strategiją, taikomą "SharePoint" svetainėms, ir modifikuokite strategiją, kad komandos, kurioje yra privatus kanalas, "Sharepoint" svetainė nebūtų įtraukta į saugojimo strategiją.</span><span class="sxs-lookup"><span data-stu-id="1f3f7-109">Identify any policy that applies to Sharepoint sites, and modify the policy so the Sharepoint site for the Team containing the private channel is NOT included under the retention policy.</span></span>
4. <span data-ttu-id="1f3f7-110">Įrašykite strategiją.</span><span class="sxs-lookup"><span data-stu-id="1f3f7-110">Save the policy.</span></span>
    <span data-ttu-id="1f3f7-111">Gali praeiti iki 24 valandų, kad įsigaliotų strategijos parametrai.</span><span class="sxs-lookup"><span data-stu-id="1f3f7-111">It can take up to 24 hours for policy settings to take effect.</span></span>
    <span data-ttu-id="1f3f7-112">Išskirę svetainę, galite ištrinti privatų kanalą.</span><span class="sxs-lookup"><span data-stu-id="1f3f7-112">After the site has been excluded, you can delete the private channel.</span></span>  
    
<span data-ttu-id="1f3f7-113">Galite ***might*** ištrinti privatų kanalą naudodami "Microsoft Teams" savo "Android" įrenginyje.</span><span class="sxs-lookup"><span data-stu-id="1f3f7-113">You  ***might*** be able to delete the private channel by using Microsoft Teams on your Android device.</span></span> 

<span data-ttu-id="1f3f7-114">Susijusios SharePoint informacijos [ieškokite Neįmanoma panaikinti elementų SharePoint Online "arba" OneDrive verslui](https://docs.microsoft.com/alchemyinsights/retention-policy-ediscovery-hold).</span><span class="sxs-lookup"><span data-stu-id="1f3f7-114">For related SharePoint information, see [Unable to delete items in SharePoint Online or OneDrive for Business](https://docs.microsoft.com/alchemyinsights/retention-policy-ediscovery-hold).</span></span>