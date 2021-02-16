---
title: Įgalinti įrenginį
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003257"
- "8278"
ms.openlocfilehash: 9e4b03dcba7a2c98a5d63213ee49f9ba8f91d670
ms.sourcegitcommit: 0470a728d184ceb89d1419f7ed57166e07bb778b
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 02/15/2021
ms.locfileid: "50256873"
---
# <a name="enable-device"></a>Įgalinti įrenginį

**Norėdami įgalinti įrenginį naudodami komandą PowerShell**

Vykdykite toliau pateiktas komandas.

- Norėdami gauti įrenginio objektą: `Get-MsolDevice -Name <Name>`
- Norėdami įgalinti įrenginį: `Enable-MsolDevice -DeviceId <DeviceId>`

Daugiau informacijos, kaip konfigūruoti hibridinio sujungimo valdomuosius domenus, ieškokite [hibridinio sujungimo konfigūravimas](https://docs.microsoft.com/azure/active-directory/devices/hybrid-azuread-join-managed-domains).
