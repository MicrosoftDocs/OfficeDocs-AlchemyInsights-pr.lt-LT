---
title: "\"Microsoft 365\" grupės siuntimas"
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 08/19/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003200"
ms.openlocfilehash: cfb4bd5ce59eeccdd0812d013b8a444aebeb1d4c
ms.sourcegitcommit: 9818d3c8e6b10f23244e51286e2463caf48fffd5
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 08/21/2020
ms.locfileid: "46871970"
---
# <a name="send-as-microsoft-365-group"></a>"Microsoft 365" grupės siuntimas

Galite priskirti siųsti kaip teises, kad konkretūs vartotojai galėtų siųsti laišką kaip "Microsoft 365" grupę:  

1. Prisijungimas prie "Exchange Online" "PowerShell".  

2. Vykdykite toliau nurodytą komandą.  

    Pridėti-RecipientPermission `<GroupName>` -patikėtinis `<MailboxName>` – prieigos teisės SendAs

Daugiau informacijos ieškokite skyriuje [leisti nariams išsiųsti kaip arba nusiųsti grupės vardu](https://docs.microsoft.com/microsoft-365/admin/create-groups/allow-members-to-send-as-or-send-on-behalf-of-group?view=o365-worldwide).