---
title: BlockLegacyAuth
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3154"
- "9001194"
ms.openlocfilehash: 06ded694893c020f862864215700853b19d35f08
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 04/15/2021
ms.locfileid: "51820186"
---
# <a name="blocking-legacy-authentication"></a><span data-ttu-id="65b49-102">Senstelėjusios įrangos autentifikavimo blokavimas</span><span class="sxs-lookup"><span data-stu-id="65b49-102">Blocking legacy authentication</span></span>

<span data-ttu-id="65b49-103">Senstelėjusis autentifikavimas yra terminas, kuris nurodo autentifikavimo užklausą, kurią pateikė:</span><span class="sxs-lookup"><span data-stu-id="65b49-103">Legacy authentication is a term that refers to an authentication request made by:</span></span>

- <span data-ttu-id="65b49-104">Senesni "Office" klientai, kurie naudoja ne modernų autentifikavimą (pvz., "Office 2010" klientą).</span><span class="sxs-lookup"><span data-stu-id="65b49-104">Older Office clients that do not use modern authentication (for example, Office 2010 client).</span></span>

- <span data-ttu-id="65b49-105">Bet kuris klientas, kuris naudoja senesnius pašto protokolus, pvz., IMAP/SMTP/POP3.</span><span class="sxs-lookup"><span data-stu-id="65b49-105">Any client that uses legacy mail protocols such as IMAP/SMTP/POP3.</span></span>

<span data-ttu-id="65b49-106">Daugiau informacijos, kaip blokuoti senstelėjusį autentifikavimą ir įgalinti modernų autentifikavimą, žr. [Senstelėjusios įrangos autentifikavimo blokavimas.](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-conditional-access-block-legacy-authentication)</span><span class="sxs-lookup"><span data-stu-id="65b49-106">For more information on blocking legacy authentication and enabling modern authentication, refer to [Blocking legacy authentication](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-conditional-access-block-legacy-authentication).</span></span>

<span data-ttu-id="65b49-107">Pagal numatytuosius saugos parametrus "Azure Active Directory" ("Azure AD") lengviau būti saugiems ir apsaugoti organizaciją.</span><span class="sxs-lookup"><span data-stu-id="65b49-107">Security defaults in Azure Active Directory (Azure AD) make it easier to be secure and help protect your organization.</span></span> <span data-ttu-id="65b49-108">Saugos numatytosiose nuostatose yra iš anksto sukonfigūruoti dažnai pasitaikančių atakų saugos parametrai.</span><span class="sxs-lookup"><span data-stu-id="65b49-108">Security defaults contain preconfigured security settings for common attacks.</span></span>
<span data-ttu-id="65b49-109">Daugiau informacijos apie saugos numatytąsias reikšmes žr. [Kas yra saugos numatytosios programos?](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults).</span><span class="sxs-lookup"><span data-stu-id="65b49-109">For more information about security defaults, refer to [What are security defaults?](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults).</span></span> 

<span data-ttu-id="65b49-110">**Pastaba:** jei jūsų nuomotojas buvo sukurtas 2019 m. spalio 22 d. arba vėliau, gali būti, kad jums kyla naujas saugus pagal numatytuosius parametrus veikimas ir jūsų nuomotoje jau yra įgalinti saugos numatytieji parametrai.</span><span class="sxs-lookup"><span data-stu-id="65b49-110">**Note**:  If your tenant was created on or after October 22nd, 2019, it's possible you are experiencing the new secure-by-default behavior and already have security defaults enabled in your tenant.</span></span>  <span data-ttu-id="65b49-111">Siekiant apsaugoti visus mūsų vartotojus, saugos numatytieji parametrai kuriami visiems naujiems nuomotojams.</span><span class="sxs-lookup"><span data-stu-id="65b49-111">In an effort to protect all of our users, security defaults is being rolled out to all new tenants created.</span></span>
