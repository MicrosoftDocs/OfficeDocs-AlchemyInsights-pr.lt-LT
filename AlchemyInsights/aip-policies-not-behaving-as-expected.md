---
title: 'AIP: strategijos neveikia taip, kaip tikėtasi'
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002266"
- "4780"
ms.openlocfilehash: 7baa010cc0b18b5d2a295623639fabf2bc5f88ec
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 04/15/2021
ms.locfileid: "51821635"
---
# <a name="aip-policies-not-behaving-as-expected"></a><span data-ttu-id="4391c-102">AIP: strategijos neveikia taip, kaip tikėtasi</span><span class="sxs-lookup"><span data-stu-id="4391c-102">AIP: Policies not behaving as expected</span></span>

<span data-ttu-id="4391c-103">"Azure" informacijos apsauga: strategijos neveikia taip, kaip tikėtasi, žr. toliau pateikiamas rekomendacijas dėl įvairių strategijos problemų:</span><span class="sxs-lookup"><span data-stu-id="4391c-103">Azure Information Protection: Policies not behaving as expected, see the following for recommended guidelines for various policy issues:</span></span>

1. <span data-ttu-id="4391c-104">Jei kyla vaizdinių žymų problemų, peržiūrėkite [Kai taikomi vaizdiniai ženklai](https://docs.microsoft.com/azure/information-protection/configure-policy-markings#when-visual-markings-are-applied).</span><span class="sxs-lookup"><span data-stu-id="4391c-104">If you are having issues with visual markings, please review [When visual markings are applied](https://docs.microsoft.com/azure/information-protection/configure-policy-markings#when-visual-markings-are-applied).</span></span>
2. <span data-ttu-id="4391c-105">Jei kyla problemų dėl automatinio etikečių žymėjimo, peržiūrėkite Kaip sukonfigūruoti automatinio ir rekomenduojamo ["Azure"](https://docs.microsoft.com/azure/information-protection/configure-policy-classification) informacijos apsaugos klasifikavimo sąlygas ir Kaip ieškoti [slaptos informacijos tipų.](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span><span class="sxs-lookup"><span data-stu-id="4391c-105">If you are having issues with automatic labeling, please review [How to configure conditions for automatic and recommended classification for Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy-classification) and [What the sensitive information types look for](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions).</span></span>
3. <span data-ttu-id="4391c-106">Jei kyla problemų dėl vietinės / Pfile apsaugos, peržiūrėkite [Failų API konfigūracija](https://docs.microsoft.com/azure/information-protection/develop/file-api-configuration).</span><span class="sxs-lookup"><span data-stu-id="4391c-106">If you are having issues with Native/Pfile protection, please review [File API configuration](https://docs.microsoft.com/azure/information-protection/develop/file-api-configuration).</span></span>
4. <span data-ttu-id="4391c-107">Patikrinkite, ar naudojate aprėpties strategijas, kurios nėra tinkamai sukonfigūruotos: Kaip konfigūruoti "Azure" informacijos apsaugos strategiją konkretiems vartotojams [naudojant aprėpties strategijas.](https://docs.microsoft.com/azure/information-protection/configure-policy-scope)</span><span class="sxs-lookup"><span data-stu-id="4391c-107">Check if you are using scoped policies that aren't configured properly: [How to configure the Azure Information Protection policy for specific users by using scoped policies](https://docs.microsoft.com/azure/information-protection/configure-policy-scope).</span></span>
5. <span data-ttu-id="4391c-108">Jei pridedant pažymėtą dokumentą "Outlook" neveikia automatinis ženklinimas, patikrinkite, ar DRMEncryptProperty nėra apibrėžtas, kaip aprašyta [čia: IRM](https://docs.microsoft.com/deployoffice/security/protect-sensitive-messages-and-documents-by-using-irm-in-office#office-2016-irm-registry-key-options)registro saugos parametrai.</span><span class="sxs-lookup"><span data-stu-id="4391c-108">If automatic labeling isn't working for Outlook when attaching a labeled document, verify that DRMEncryptProperty isn't defined as described here: [IRM registry settings for security](https://docs.microsoft.com/deployoffice/security/protect-sensitive-messages-and-documents-by-using-irm-in-office#office-2016-irm-registry-key-options).</span></span>

<span data-ttu-id="4391c-109">Jei vis dar kyla problemų, rinkite "Azure" informacijos apsaugos kliento žurnalus ir pridėkite eksportuotus žurnalus prie šio kvito.</span><span class="sxs-lookup"><span data-stu-id="4391c-109">If you still are experiencing issues, please collect Azure Information Protection client logs and attach the exported logs to this ticket.</span></span>

1. <span data-ttu-id="4391c-110">Atidarykite "Office" dokumentą arba sukurkite naują el. laišką programoje "Outlook".</span><span class="sxs-lookup"><span data-stu-id="4391c-110">Open an Office document or create a new email in Outlook.</span></span>
2. <span data-ttu-id="4391c-111">Spustelėkite **Apsaugoti / slaptumo**  >  **žinyną ir atsiliepimus.**</span><span class="sxs-lookup"><span data-stu-id="4391c-111">Click **Protect/Sensitivity** > **Help and feedback**.</span></span>
3. <span data-ttu-id="4391c-112">Spustelėkite **Eksportuoti žurnalus.**</span><span class="sxs-lookup"><span data-stu-id="4391c-112">Click **Export Logs**.</span></span>
4. <span data-ttu-id="4391c-113">Įrašykite žurnalus į savo vietą ir pridėkite juos prie šios tarnybos užklausos.</span><span class="sxs-lookup"><span data-stu-id="4391c-113">Save the logs to your choice of location, and attach them to this service request.</span></span>

<span data-ttu-id="4391c-114">Papildomi ištekliai:</span><span class="sxs-lookup"><span data-stu-id="4391c-114">Additional resources:</span></span>

- [<span data-ttu-id="4391c-115">Kaip konfigūruoti "Azure" informacijos apsaugos vaizdinių žymų etiketę</span><span class="sxs-lookup"><span data-stu-id="4391c-115">How to configure a label for visual markings for Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/configure-policy-markings)
- [<span data-ttu-id="4391c-116">Peržiūrėkite "Azure" informacijos apsaugos dokumentaciją</span><span class="sxs-lookup"><span data-stu-id="4391c-116">Review Azure Information Protection documentation</span></span>](https://docs.microsoft.com/azure/information-protection/what-is-information-protection)
- [<span data-ttu-id="4391c-117">Slaptumo etikečių naudojimas "Microsoft 365" programose</span><span class="sxs-lookup"><span data-stu-id="4391c-117">Use sensitivity labels in Microsoft 365 apps</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels-office-apps)

