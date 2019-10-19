---
title: Kaip išjungti išorinių grupių
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "966"
- "6000006"
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: b2328ea85d3ff6ec722cc56d8a46395d8438f79c
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 10/18/2019
ms.locfileid: "36739501"
---
# <a name="how-to-disable-external-groups"></a><span data-ttu-id="ae9a0-102">Kaip išjungti išorinių grupių</span><span class="sxs-lookup"><span data-stu-id="ae9a0-102">How to disable External Groups</span></span>

<span data-ttu-id="ae9a0-103">"Yammer" išoriniai pranešimai taiko "Exchange" transportavimo taisykles (ETRs) – aktyvių valdiklių rinkinį, kad įmonės informacija nebūtų bendrinama.</span><span class="sxs-lookup"><span data-stu-id="ae9a0-103">Yammer external messaging applies Exchange Transport Rules (ETRs), a set of proactive controls to prevent company information from being shared.</span></span> <span data-ttu-id="ae9a0-104">Tam, kad vartotojams būtų apribotas išorinių grupių kūrimas, turite sukonfigūruoti "Exchange" transportavimo taisyklę (ETR) ir sukonfigūruoti "Yammer", kad būtų galima naudoti "Exchange" transportavimo taisyklę, kad būtų užblokuoti išoriniai pranešimai.</span><span class="sxs-lookup"><span data-stu-id="ae9a0-104">In order to restrict users from creating external groups, you need to configure an Exchange transport rule (ETR), and then configure Yammer to use the Exchange Transport rule to block external messaging.</span></span>
  
<span data-ttu-id="ae9a0-105">Sukūrę taisyklę "Exchange Online" administravimo centre, atlikite šiuos veiksmus, kad nustatyti ETR, kad būtų taikoma "Yammer":</span><span class="sxs-lookup"><span data-stu-id="ae9a0-105">Once you have created a rule in Exchange Online admin center, follow these steps to set ETR to apply in Yammer:</span></span>
  
- <span data-ttu-id="ae9a0-106">Įeikite į "Yammer" kaip patvirtintą administratorių, o " **Yammer" administravimo centre**eikite į C **turinį ir saugos \> saugos parametrus.**</span><span class="sxs-lookup"><span data-stu-id="ae9a0-106">Log on to Yammer as a verified admin, and in the **Yammer admin center**, go to C **Content and Security \> Security Settings.**</span></span>

- <span data-ttu-id="ae9a0-107">Dalyje **išoriniai pranešimai**pasirinkite **įgalinti "Yammer" Exchange Online Exchange transportavimo taisykles (etrs).**</span><span class="sxs-lookup"><span data-stu-id="ae9a0-107">Under **External Messaging**, select **Enforce your Exchange Online Exchange Transport Rules (ETRs) in Yammer.**</span></span>

- <span data-ttu-id="ae9a0-108">Pasirinkite **įrašyti**.</span><span class="sxs-lookup"><span data-stu-id="ae9a0-108">Choose **Save**.</span></span>

<span data-ttu-id="ae9a0-109">Daugiau informacijos rasite [išjungti išorinius pranešimus "Yammer" tinkle](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).</span><span class="sxs-lookup"><span data-stu-id="ae9a0-109">For more information, see [Disable external messaging in a Yammer network](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).</span></span>
  