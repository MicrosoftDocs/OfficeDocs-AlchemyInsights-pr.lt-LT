---
title: Valdyti sinchronizuoto vartotojo
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: 5a383bdd17c5fa055c35a923ca36e0e0f6d429e4
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 06/28/2019
ms.locfileid: "35380513"
---
# <a name="unable-to-set-primary-email-address-or-change-user-attributes"></a><span data-ttu-id="63e7b-102">Neįmanoma nustatyti pagrindinį el. pašto adresą arba pakeisti vartotojo atributus</span><span class="sxs-lookup"><span data-stu-id="63e7b-102">Unable to set primary email address or change user attributes</span></span>

<span data-ttu-id="63e7b-103">Jei katalogų sinchronizavimo yra įjungta jūsų aplinkoje kai vartotojas ar objekto atributų negalima keisti naudojant administravimo centrą.</span><span class="sxs-lookup"><span data-stu-id="63e7b-103">If directory synchronization is enabled for your environment some user or object attributes cannot be changed using the Admin Center.</span></span>
<span data-ttu-id="63e7b-104">Visiškai valdyti sinchronizuota vartotojams ir jų atributus, naudokite savo vietos Aktyvaus katalogo vartotojus ir grupes valdymo pultą (adsiedit.msc).</span><span class="sxs-lookup"><span data-stu-id="63e7b-104">To fully manage synchronized users and all their attributes, use your local active directory users and groups management console (adsiedit.msc).</span></span>  

<span data-ttu-id="63e7b-105">Taip pat galite keisti atskirų vartotojų arba atributai sinchronizuota vartotojams naudojant "PowerShell", kaip parodyta šių pavyzdžių:</span><span class="sxs-lookup"><span data-stu-id="63e7b-105">Alternatively, you can change individual users or attributes for synchronized users using powershell such as shown in these common examples:</span></span> 
- <span data-ttu-id="63e7b-106">Rinkinys-MsolUser - UserPrincipalName user@yourdomain.onmicrosoft.com - AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="63e7b-106">Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span></span>
- <span data-ttu-id="63e7b-107">Rinkinys-MsolUser - UserPrincipalName "user@yourdomain.onmicrosoft.com" - DisplayName "Bandomojo vartotojo" - pavardė "Vartotojas"-pavadinimas "Manager"-skyrius "HR"</span><span class="sxs-lookup"><span data-stu-id="63e7b-107">Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"</span></span>
- <span data-ttu-id="63e7b-108">Pašalinti-MsolUser - UserPrincipalName "user@yourdomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="63e7b-108">Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com</span></span>