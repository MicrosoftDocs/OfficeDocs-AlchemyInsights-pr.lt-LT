---
title: Pašto dėžučių tikrinimo įjungimas
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/26/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3100005"
- "7327"
ms.openlocfilehash: aa0ff925ae891d28e31394ec66eb17c2d9710008
ms.sourcegitcommit: 251e2e82571fb3bb1fbe3dbf7bfca30e004b3373
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 03/05/2021
ms.locfileid: "50482472"
---
# <a name="turn-on-mailbox-auditing"></a>Pašto dėžučių tikrinimo įjungimas

Norėdami įjungti vieno vartotojo ar visos organizacijos pašto dėžučių tikrinimą, paleiskite šias "cmdlet" iš "Remote PowerShell":

- **Vienas vartotojas**: Set-Mailbox-tapatybė "Jane Dow"-AuditEnabled $TRUE
- **Organizacija**: Get-Mailbox-Resultisize Unlimited-filtruoti {RecipientTypeDetails-EQ "UserMailbox"} | Set-Mailbox – AuditEnabled $true

Norėdami sužinoti daugiau, peržiūrėkite [pašto dėžutės tikrinimo tvarkymas](https://go.microsoft.com/fwlink/?linkid=2103668).