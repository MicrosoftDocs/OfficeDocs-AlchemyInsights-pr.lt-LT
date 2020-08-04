---
title: Suplanuotų naujinimų pristabdymas
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/30/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1129"
- "6700007"
ms.openlocfilehash: 9dc0f387cf63557e2a1f81ca8f3c3ca9998170ca
ms.sourcegitcommit: d1c51266e2890f61662f77dceea2ad0c88210015
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 07/30/2020
ms.locfileid: "46555512"
---
# <a name="pausing-scheduled-updates"></a><span data-ttu-id="ec2e5-102">Suplanuotų naujinimų pristabdymas</span><span class="sxs-lookup"><span data-stu-id="ec2e5-102">Pausing scheduled updates</span></span>

<span data-ttu-id="ec2e5-103">Kai pristabdymo komanda išduodama, įrenginiai nepervalo komandos, kol kitą kartą jie prisiregistruoja į "Intune".</span><span class="sxs-lookup"><span data-stu-id="ec2e5-103">When a pause command is issued, devices don't process the command until the next time they check in to Intune.</span></span> <span data-ttu-id="ec2e5-104">Dėl šios priežasties jūsų įrenginiai gali turėti:</span><span class="sxs-lookup"><span data-stu-id="ec2e5-104">Because of this, your devices might have:</span></span>

- <span data-ttu-id="ec2e5-105">Prieš įsiregistruodami įdiegti suplanuoti naujinimai.</span><span class="sxs-lookup"><span data-stu-id="ec2e5-105">Installed the scheduled updates prior to check-in.</span></span>
- <span data-ttu-id="ec2e5-106">Buvo išjungtas, kai išdavėte komandą pauzė.</span><span class="sxs-lookup"><span data-stu-id="ec2e5-106">Been powered off when you issued the pause command.</span></span> <span data-ttu-id="ec2e5-107">Tokiu atveju, kai įrenginiai buvo įjungti, jie galėjo atsisiųsti ir įdiegti suplanuotus naujinimus prieš registruojantis.</span><span class="sxs-lookup"><span data-stu-id="ec2e5-107">In this case, when the devices were powered on, they might have downloaded and installed the scheduled updates prior to check-in.</span></span>