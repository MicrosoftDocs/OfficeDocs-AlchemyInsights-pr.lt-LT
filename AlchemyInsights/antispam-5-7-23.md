---
title: Apsaugos nuo brukalo - 5.7.23
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3156"
- "9001196"
ms.openlocfilehash: 8122b409a731a5fcc46c718aff1eeda07e26890b
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506451"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a><span data-ttu-id="c6587-102">El. pašto pristatymo problemų sprendimas klaidos kodas 5.7.23</span><span class="sxs-lookup"><span data-stu-id="c6587-102">Fix email delivery issues for error code 5.7.23</span></span>

<span data-ttu-id="c6587-103">Patikrinkite savo domeno SPF DNS įrašą viešai prieinamoje SPF arba DNS įrašų tikrintuve žiniatinklyje.</span><span class="sxs-lookup"><span data-stu-id="c6587-103">Verify the SPF DNS record for your domain at a publicly available SPF or DNS record checker on the web.</span></span>

<span data-ttu-id="c6587-104">Patikrinkite, ar "Microsoft" nenustatė siunčiamo pranešimo kaip pašto šiukšlių ir nurodė per [didelės rizikos pristatymo telkinį](https://docs.microsoft.com/microsoft-365/security/office-365-security/high-risk-delivery-pool-for-outbound-messages).</span><span class="sxs-lookup"><span data-stu-id="c6587-104">Verify that the outbound message wasn't identified as spam by Microsoft and routed through the [High Risk Delivery Pool](https://docs.microsoft.com/microsoft-365/security/office-365-security/high-risk-delivery-pool-for-outbound-messages).</span></span> <span data-ttu-id="c6587-105">Didelės rizikos pristatymo telkinio pranešimai neišlaikys SPF patikrinimų, todėl paskirties el. pašto organizacija jų nepriims.</span><span class="sxs-lookup"><span data-stu-id="c6587-105">Messages in the High Risk Delivery Pool won't pass SPF checks, and therefore won't be accepted by the destination email organization.</span></span>

<span data-ttu-id="c6587-106">Jei problema išlieka, gali tekti susisiekti su pašto pagrindinio kompiuterio, į kurį bandote siųsti el. laiškus, administratoriumi.</span><span class="sxs-lookup"><span data-stu-id="c6587-106">If the problem persists, you may need to contact the admin of the mail host to which you are attempting to send email.</span></span> <span data-ttu-id="c6587-107">Užsirašykite išsamią išorinę klaidą, pasiekiamą atmetimo pranešime.</span><span class="sxs-lookup"><span data-stu-id="c6587-107">Make note of the detailed external error available in the bounce message.</span></span> <span data-ttu-id="c6587-108">"Microsoft" palaikymo tarnyba gali negalėti toliau padėti.</span><span class="sxs-lookup"><span data-stu-id="c6587-108">Microsoft support may not be able to assist further.</span></span>
