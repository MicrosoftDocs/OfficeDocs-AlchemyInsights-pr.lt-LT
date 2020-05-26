---
title: Pasveikinimo pranešimas "Microsoft 365" grupėse
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "5685"
ms.openlocfilehash: d82931ae6978a09e674b00640d1dd413bcce7cfd
ms.sourcegitcommit: b196100759b29aecd62b693a2bfedbbd25a697c6
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 05/19/2020
ms.locfileid: "44357840"
---
# <a name="welcome-message-in-microsoft-365-groups"></a>Pasveikinimo pranešimas "Microsoft 365" grupėse

Nauji vartotojai, prisijungiantys prie "Microsoft 365" grupės gaus pasveikinimo el. laišką, jei ypatybė "UnifiedGroupWelcomeMessageEnabled" yra teisinga.

Jei norite išjungti pasveikinimo pranešimą, naudokite šią komandą [EXO "PowerShell":](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps)

`
Set-UnifiedGroup <groupname> -UnifiedGroupWelcomeMessageEnabled:$False
`
