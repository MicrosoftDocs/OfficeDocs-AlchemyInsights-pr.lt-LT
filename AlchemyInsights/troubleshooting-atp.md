---
title: "\"Office 365\" išplėstinės apsaugos nuo grėsmių trikčių diagnostika"
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1039
ms.assetid: ''
ms.openlocfilehash: c90c8e9cb23cba93883cc1148fcbca77c9e92408
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 04/22/2020
ms.locfileid: "43732410"
---
# <a name="troubleshooting-office-365-advanced-threat-protection"></a><span data-ttu-id="e809a-102">"Office 365" išplėstinės apsaugos nuo grėsmių trikčių diagnostika</span><span class="sxs-lookup"><span data-stu-id="e809a-102">Troubleshooting Office 365 Advanced Threat Protection</span></span>

- <span data-ttu-id="e809a-103">Ar pastebite pranešimų pristatymo vėlavimą?</span><span class="sxs-lookup"><span data-stu-id="e809a-103">Do you notice delays in message delivery?</span></span> <span data-ttu-id="e809a-104">Naudokite [atsaugaus](https://docs.microsoft.com/office365/securitycompliance/dynamic-delivery-and-previewing) priedų strategijos parinktį Dinaminis pristatymas.</span><span class="sxs-lookup"><span data-stu-id="e809a-104">Use the [Dynamic Delivery](https://docs.microsoft.com/office365/securitycompliance/dynamic-delivery-and-previewing) option in your ATP Safe Attachments policy.</span></span> <span data-ttu-id="e809a-105">Tai padės išvengti pranešimų delsos apsaugant gavėjus nuo kenkėjiškų failų.</span><span class="sxs-lookup"><span data-stu-id="e809a-105">This will help avoid message delays while protecting recipients from malicious files.</span></span>

- <span data-ttu-id="e809a-106">Ar norite pranešti "Microsoft" apie klaidingus teigiamus arba klaidingus negatyvus?</span><span class="sxs-lookup"><span data-stu-id="e809a-106">Do you want to report false positives or false negatives to Microsoft?</span></span> <span data-ttu-id="e809a-107">Naudokite šį [saitą](https://www.microsoft.com/wdsi/filesubmission/) norėdami pateikti analizei failus.</span><span class="sxs-lookup"><span data-stu-id="e809a-107">Use this [link](https://www.microsoft.com/wdsi/filesubmission/) to submit files for analysis.</span></span>

- <span data-ttu-id="e809a-108">Ar žinojote, kad galite įgalinti saugių saitų apsaugą vidiniams el. laiškams, siunčiamiems tarp jūsų organizacijos gavėjų?</span><span class="sxs-lookup"><span data-stu-id="e809a-108">Did you know that you can enable Safe Links protection for internal email sent between recipients within your organization?</span></span> <span data-ttu-id="e809a-109">Atlikite šiuos veiksmus:</span><span class="sxs-lookup"><span data-stu-id="e809a-109">Follow these steps:</span></span>

  1. <span data-ttu-id="e809a-110">Eikite [https://protection.office.com](https://protection.office.com) į visuotinio administratoriaus arba saugos administratoriaus abonementą ir prisijunkite naudodami.</span><span class="sxs-lookup"><span data-stu-id="e809a-110">Go to [https://protection.office.com](https://protection.office.com) and sign in with a global administrator or security administrator account.</span></span>

  2. <span data-ttu-id="e809a-111">Kairiosios naršymo srities dalyje **Grėsmių valdymas**pasirinkite **Strategijos** \> **saugios nuorodos**.</span><span class="sxs-lookup"><span data-stu-id="e809a-111">In the left navigation pane under **Threat management**, choose **Policy** \> **Safe Links**.</span></span>

  3. <span data-ttu-id="e809a-112">Sekcijoje **Strategijos, taikomos visai organizacijai,** pasirinkite strategiją ir spustelėkite **Redaguoti**.</span><span class="sxs-lookup"><span data-stu-id="e809a-112">In the **Policies that apply to the entire organization** section, select the policy and click **Edit**.</span></span>

  4. <span data-ttu-id="e809a-113">Dalyje **Parametrai**įjunkite **Taikyti saugius saitus organizacijos siunčiamiems pranešimams**.</span><span class="sxs-lookup"><span data-stu-id="e809a-113">Under **Settings**, enable **Apply safe links to messages sent within the organization**.</span></span>
