---
title: Registravimo žurnale valdymas
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004299"
- "7677"
ms.openlocfilehash: 2fcd0f386d2da8cad19fcc9872482bb75fe00dd2
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 03/11/2021
ms.locfileid: "50748658"
---
# <a name="manage-journaling"></a><span data-ttu-id="a7052-102">Registravimo žurnale valdymas</span><span class="sxs-lookup"><span data-stu-id="a7052-102">Manage journaling</span></span>

<span data-ttu-id="a7052-103">Registravimas žurnale gali padėti jūsų organizacijai atsakyti į teisinius, reguliavimo ir organizacijos atitikties reikalavimus įrašant gaunamus ir siunčiamus elektroninio pašto ryšius.</span><span class="sxs-lookup"><span data-stu-id="a7052-103">Journaling can help your organization respond to legal, regulatory, and organizational compliance requirements by recording inbound and outbound email communications.</span></span> <span data-ttu-id="a7052-104">Atminkite:</span><span class="sxs-lookup"><span data-stu-id="a7052-104">Keep in mind:</span></span>

* <span data-ttu-id="a7052-105">Kad galėtumėte valdyti registravimą žurnale, turite turėti [organizacijos valdymo](https://go.microsoft.com/fwlink/?linkid=2115259) ir [įrašo valdymo](https://go.microsoft.com/fwlink/?linkid=2115469) teises.</span><span class="sxs-lookup"><span data-stu-id="a7052-105">You need to have [Organization Management](https://go.microsoft.com/fwlink/?linkid=2115259) and [Records Management](https://go.microsoft.com/fwlink/?linkid=2115469) permissions before you can manage journaling.</span></span>
* <span data-ttu-id="a7052-106">Jums reikia turėti žurnalo pašto dėžutę ir (pasirinktinai) kitą registravimo žurnale pašto dėžutę.</span><span class="sxs-lookup"><span data-stu-id="a7052-106">You need to have a journal mailbox and (optionally) an alternate journaling mailbox configured.</span></span> <span data-ttu-id="a7052-107">Daugiau informacijos rasite " [Exchange Online" registravimo žurnale konfigūravimas](https://go.microsoft.com/fwlink/?linkid=2115260).</span><span class="sxs-lookup"><span data-stu-id="a7052-107">To learn more, see [Configure Journaling in Exchange Online](https://go.microsoft.com/fwlink/?linkid=2115260).</span></span>
* <span data-ttu-id="a7052-108">Naudojant "Exchange Online", galite sukurti "Journal" taisyklių, kurias galite sukurti, skaičiaus limitą.</span><span class="sxs-lookup"><span data-stu-id="a7052-108">In Exchange Online, there's a limit to the number of journal rules that you can create.</span></span> <span data-ttu-id="a7052-109">Išsamesnės informacijos ieškokite [žurnalo, transportavimo ir aplanko Gauta taisyklių limitai](https://go.microsoft.com/fwlink/?linkid=2115261).</span><span class="sxs-lookup"><span data-stu-id="a7052-109">For details, see [Journal, transport, and inbox rule limits](https://go.microsoft.com/fwlink/?linkid=2115261).</span></span>
* <span data-ttu-id="a7052-110">"Exchange Online" nepalaiko žurnalų ataskaitų pristatymo į "Exchange Online" pašto dėžutę.</span><span class="sxs-lookup"><span data-stu-id="a7052-110">Exchange Online doesn't support delivering journal reports to an Exchange Online mailbox.</span></span> <span data-ttu-id="a7052-111">Turite apibrėžti vietinio archyvavimo sistemos arba trečiosios šalies archyvavimo tarnybos, kaip registravimo žurnale pašto dėžutės, elektroninio pašto adresą.</span><span class="sxs-lookup"><span data-stu-id="a7052-111">You must specify the email address of an on-premises archiving system or a third-party archiving service as the journaling mailbox.</span></span>
