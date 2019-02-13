---
title: Išjungti UPN sinchronizavimo
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: 983796ce8fb7e8b52c0ce31aa13597b53cc9e038
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 02/12/2019
ms.locfileid: "29921716"
---
# <a name="upn-sync-disabled"></a><span data-ttu-id="efd27-102">Išjungti UPN sinchronizavimo</span><span class="sxs-lookup"><span data-stu-id="efd27-102">UPN sync disabled</span></span>

<span data-ttu-id="efd27-103">Jei pradėjote sinchronizavimą su Azure AD iki 2016 kovo 30 vykdyti šį Azure AD PowerShell cmdlet, kad UPN minkštas tinka jūsų organizacijai tik:</span><span class="sxs-lookup"><span data-stu-id="efd27-103">If you started syncing to Azure AD before March 30, 2016, run the following Azure AD PowerShell cmdlet to enable UPN soft match for your organization only:</span></span>
  
 <span data-ttu-id="efd27-104">**Rinkinys-MsolDirSyncFeature-EnableSoftMatchOnUpn funkcija-leidžia $True**</span><span class="sxs-lookup"><span data-stu-id="efd27-104">**Set-MsolDirSyncFeature -Feature EnableSoftMatchOnUpn -Enable $True**</span></span>
  
<span data-ttu-id="efd27-105">UPN minkštas rungtynės įjungiamas automatiškai, organizacijose, kuriose pradėti sinchronizavimą su Azure AD arba po 2016 m. kovo 30 d.</span><span class="sxs-lookup"><span data-stu-id="efd27-105">UPN soft match is automatically turned on for organizations that started syncing to Azure AD on or after March 30, 2016.</span></span>
  
<span data-ttu-id="efd27-106">Norėdami sužinoti daugiau apie įgalinimą minkštas rungtynės UPN ir kitus sinchronizavimo funkcijos, prašome peržiūrėti [Azure AD Connect sinchronizavimo tarnybos funkcijas](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span><span class="sxs-lookup"><span data-stu-id="efd27-106">To learn more about enabling soft match on UPN and other sync features, please see [Azure AD Connect sync service features](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span></span>
  

