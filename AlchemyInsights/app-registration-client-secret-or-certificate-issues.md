---
title: Programos registracijos kliento slaptos arba sertifikato problemos
ms.author: v-jmathew
author: v-jmathew
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004352"
- "9685"
ms.openlocfilehash: 990648d286ec801785201e6513b70534c3d80e3f
ms.sourcegitcommit: 1f43598a726cdb9904aa501eb8db87f143020d9e
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 03/23/2021
ms.locfileid: "51404783"
---
# <a name="app-registration-client-secret-or-certificate-issues"></a><span data-ttu-id="6a6c9-102">Programos registracijos kliento slaptos arba sertifikato problemos</span><span class="sxs-lookup"><span data-stu-id="6a6c9-102">App Registration client secret or Certificate issues</span></span>

<span data-ttu-id="6a6c9-103">Programos kliento paslaptis baigiasi?</span><span class="sxs-lookup"><span data-stu-id="6a6c9-103">Application client secret expiring?</span></span>

<span data-ttu-id="6a6c9-104">Neatsižvelgiant į tai, kaip buvo sukurta registruota taikomoji programa, ar naudojant standartinį registracijos procesą taikomųjų programų registracijos portale, ar jūsų nuomotoje buvo sukurta pagrindinė paslaugų teikimo vieta naudojant taikomosios programos sutikimą, prieš pasibaigiant dabartiniam kliento kodui reikės sukurti naują kliento paslaptį ir atnaujinti jį susijusiame programos kode.</span><span class="sxs-lookup"><span data-stu-id="6a6c9-104">Regardless of how the registered application was created, whether through the standard registration process in the Apps Registration portal or if the Service Principal was created in your tenant using application consent, a new Client Secret will need to be created prior to the expiration of the current one and updated in the related application code.</span></span> <span data-ttu-id="6a6c9-105">Maksimalus galiojimo laikotarpis yra 2 metai.</span><span class="sxs-lookup"><span data-stu-id="6a6c9-105">The maximum validity period is 2 years.</span></span> <span data-ttu-id="6a6c9-106">Kaip priminimą slapta reikšmė turi būti įrašyta, nes ji nebebus matoma portale išeidami iš taikomųjų programų registracijos puslapio.</span><span class="sxs-lookup"><span data-stu-id="6a6c9-106">As a reminder the secret value must be recorded as it will no longer be visible after leaving the App registrations page in the portal.</span></span> <span data-ttu-id="6a6c9-107">Daugiau informacijos žr. ["Quickstart": taikomosios programos registravimas "Microsoft"](https://docs.microsoft.com/azure/active-directory/develop/quickstart-register-app) tapatybės platformoje [ir geriausia "Microsoft" tapatybės platformos praktika.](https://docs.microsoft.com/azure/active-directory/develop/identity-platform-integration-checklist#security)</span><span class="sxs-lookup"><span data-stu-id="6a6c9-107">For more information, see [Quickstart: Register an app in the Microsoft identity platform](https://docs.microsoft.com/azure/active-directory/develop/quickstart-register-app) and [Best practices for the Microsoft identity platform](https://docs.microsoft.com/azure/active-directory/develop/identity-platform-integration-checklist#security).</span></span>

<span data-ttu-id="6a6c9-108">Norėdami sužinoti daugiau, [žr. "Azure AD" programos kūrimas & pagrindinė tarnyba portale – "Microsoft" tapatybės platforma](https://docs.microsoft.com/azure/active-directory/develop/howto-create-service-principal-portal).</span><span class="sxs-lookup"><span data-stu-id="6a6c9-108">To learn more, see [Create an Azure AD app & service principal in the portal - Microsoft identity platform](https://docs.microsoft.com/azure/active-directory/develop/howto-create-service-principal-portal).</span></span>