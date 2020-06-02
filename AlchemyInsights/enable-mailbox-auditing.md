---
title: Įgalinti pašto dėžučių tikrinimą
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 2bcfb7cc174cd58b21e1bb0c82f0d7cdb25e2fdd
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506962"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="8eb43-102">Įgalinti pašto dėžučių tikrinimą</span><span class="sxs-lookup"><span data-stu-id="8eb43-102">Enable mailbox auditing</span></span>

<span data-ttu-id="8eb43-103">Norėdami įgalinti pašto dėžutės tikrinimo vieną vartotoją arba visą organizaciją, šie cmdlet turi būti paleisti iš nuotolinio maitinimo aplinkoje:</span><span class="sxs-lookup"><span data-stu-id="8eb43-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="8eb43-104">**Vienas vartotojas**</span><span class="sxs-lookup"><span data-stu-id="8eb43-104">**Single User**</span></span>
  
<span data-ttu-id="8eb43-105">Set-Mailbox -tapatybės "Jane Dow" - AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="8eb43-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="8eb43-106">**Organizacijos**</span><span class="sxs-lookup"><span data-stu-id="8eb43-106">**Organization**</span></span>
  
<span data-ttu-id="8eb43-107">Get-Mailbox -ResultSize Neribotas -Filtras {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox - AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="8eb43-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="8eb43-108">sužinoti daugiau, sužinok daugiau</span><span class="sxs-lookup"><span data-stu-id="8eb43-108">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/enable-mailbox-auditing)
  

