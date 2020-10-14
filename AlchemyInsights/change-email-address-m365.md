---
title: "\"Microsoft 365\" grupės elektroninio pašto adreso keitimas"
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "4704"
ms.openlocfilehash: f54ca5df09d0604f6d58c6c8a41dc907485e1f04
ms.sourcegitcommit: beb9715ac0c8e8333fef6764ecd346b7401a2612
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 10/10/2020
ms.locfileid: "48461945"
---
# <a name="change-email-address-of-a-microsoft-365-group"></a>"Microsoft" 365 grupės el. pašto adreso keitimas

Galite pakeisti "Microsoft" 365 grupės el. pašto adresą naudodami administravimo centrą. Tiesiog pasirinkite grupę ir pasirinkite @edit elektroninio pašto adresą.

Taip pat galite naudoti toliau pateiktą komandą EXO PowerShell, kad pakeistumėte pirminį "Microsoft 365" grupės SMTP adresą:

`Set-UnifiedGroup <Group Name> -PrimarySmtpAddress <new SMTP Address>`

Pavyzdžiui

`et-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com`
