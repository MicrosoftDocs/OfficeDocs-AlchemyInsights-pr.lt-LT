---
title: "\"Microsoft 365\" grupės el. pašto adreso keitimas"
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
- "1200024"
- "4704"
ms.openlocfilehash: 8eaafae8650a8072cdfbec281afe6d5e93fea655
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 04/15/2021
ms.locfileid: "51819052"
---
# <a name="change-email-address-of-a-microsoft-365-group"></a><span data-ttu-id="e26cc-102">"Microsoft 365" grupės el. pašto adreso keitimas</span><span class="sxs-lookup"><span data-stu-id="e26cc-102">Change email address of a Microsoft 365 group</span></span>

<span data-ttu-id="e26cc-103">Galite pakeisti "Microsoft 365" grupės el. pašto adresą naudodami administravimo centrą.</span><span class="sxs-lookup"><span data-stu-id="e26cc-103">You can change the email address of a Microsoft 365 group by using the admin center.</span></span> <span data-ttu-id="e26cc-104">Tiesiog pasirinkite grupę ir pasirinkite @redaguoti el. pašto adresą.</span><span class="sxs-lookup"><span data-stu-id="e26cc-104">Just select the group and select @edit email address.</span></span>

<span data-ttu-id="e26cc-105">Taip pat galite naudoti exo "PowerShell" komandą norėdami pakeisti pagrindinį "Microsoft 365" grupės SMTP adresą:</span><span class="sxs-lookup"><span data-stu-id="e26cc-105">You can also use following the EXO PowerShell command to change the primary SMTP address of a Microsoft 365 group:</span></span>

<span data-ttu-id="e26cc-106">Set-UnifiedGroup <Group Name> -PrimarySmtpAddress <new SMTP Address></span><span class="sxs-lookup"><span data-stu-id="e26cc-106">Set-UnifiedGroup <Group Name> -PrimarySmtpAddress <new SMTP Address></span></span>

<span data-ttu-id="e26cc-107">Pavyzdys:</span><span class="sxs-lookup"><span data-stu-id="e26cc-107">Example:</span></span>

```
    Set-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com
```
