---
title: Slaptažodžių strategijos
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 03/11/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004595"
- "9277"
ms.openlocfilehash: 826e266d08aa68c0d4213d8058a0244f404fe965
ms.sourcegitcommit: 186281d0b87d67f041c127d4334faa937da9a48a
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 03/11/2021
ms.locfileid: "50747046"
---
# <a name="password-policies"></a><span data-ttu-id="e834d-102">Slaptažodžių strategijos</span><span class="sxs-lookup"><span data-stu-id="e834d-102">Password policies</span></span>

<span data-ttu-id="e834d-103">**Kilo problemų dėl vartotojo slaptažodžių strategijos**</span><span class="sxs-lookup"><span data-stu-id="e834d-103">**I'm having problems with the password policy for a user**</span></span>

- <span data-ttu-id="e834d-104">Vartotojo slaptažodžių strategija priklauso nuo to, ar vartotojas yra tik debesis, ar vietinis.</span><span class="sxs-lookup"><span data-stu-id="e834d-104">The password policy for a user depends on whether the user is cloud only or on-premises.</span></span>
- <span data-ttu-id="e834d-105">Tik debesies vartotojai turi pasirinkti slaptažodį, atitinkantį šio straipsnio reikalavimus: [slaptažodžių strategijos, taikomos tik debesies vartotojų paskyroms](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support#password-policies-that-only-apply-to-cloud-user-accounts)</span><span class="sxs-lookup"><span data-stu-id="e834d-105">Cloud only users must choose a password that meets the requirements in this article: [Password policies that only apply to cloud user accounts](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support#password-policies-that-only-apply-to-cloud-user-accounts)</span></span>
- <span data-ttu-id="e834d-106">Vietiniai vartotojai turi pasirinkti slaptažodį, atitinkantį vietinius reikalavimus.</span><span class="sxs-lookup"><span data-stu-id="e834d-106">On-premises users must choose a password that meets the on-premises requirements.</span></span> <span data-ttu-id="e834d-107">Jei vietinis vartotojas negali nustatyti savo slaptažodžio, patikrinkite vietinius reikalavimus.</span><span class="sxs-lookup"><span data-stu-id="e834d-107">If an on-premises user is unable to set their password, check your on-premises requirements.</span></span>

<span data-ttu-id="e834d-108">**Nežinau, kaip nustatyti arba patikrinti slaptažodžių galiojimo strategiją**</span><span class="sxs-lookup"><span data-stu-id="e834d-108">**I don't know how to set or check password expiration policies**</span></span>

- <span data-ttu-id="e834d-109">Galite nustatyti ir patikrinti savo nuomotojo debesies vartotojų galiojimo laiko strategiją naudodami "PowerShell".</span><span class="sxs-lookup"><span data-stu-id="e834d-109">You can set and check the expiration policy for cloud users in your tenant by using PowerShell.</span></span> <span data-ttu-id="e834d-110">Vadovaukitės šiame straipsnyje pateiktomis instrukcijomis: [slaptažodžių strategijų nustatymas arba tikrinimas naudojant "PowerShell](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support#set-or-check-the-password-policies-by-using-powershell) "</span><span class="sxs-lookup"><span data-stu-id="e834d-110">Follow the instructions in this article: [Set or check the password policies by using PowerShell](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support#set-or-check-the-password-policies-by-using-powershell)</span></span>
- <span data-ttu-id="e834d-111">Vietinių vartotojų slaptažodžių galiojimo strategija nustatyta jūsų vietiniame skelbime.</span><span class="sxs-lookup"><span data-stu-id="e834d-111">The password expiration policy for on-premises users is set in your on-premises AD.</span></span>

<span data-ttu-id="e834d-112">**Kiti naudingi saitai:**</span><span class="sxs-lookup"><span data-stu-id="e834d-112">**Other Helpful links:**</span></span>
- [<span data-ttu-id="e834d-113">Darbo su slaptažodžiu nustatymo iš naujo Pradžia</span><span class="sxs-lookup"><span data-stu-id="e834d-113">Getting Started with Password Reset</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support#set-or-check-the-password-policies-by-using-powershell)
- [<span data-ttu-id="e834d-114">Administratoriaus inicijuoto slaptažodžio nustatymo iš naujo trikčių diagnostika</span><span class="sxs-lookup"><span data-stu-id="e834d-114">Troubleshoot Administrator-initiated Password Reset</span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-passwords-troubleshoot?WT.mc_id=Portal-Microsoft_Azure_Support#troubleshoot-the-password-reset-portal)
