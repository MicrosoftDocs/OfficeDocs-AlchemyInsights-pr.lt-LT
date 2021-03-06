---
title: "\"DKIM\" sąrankos problemų sprendimas"
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 35e8023d26fe26211e27521ceb8751d2d7fc7a21
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 09/14/2020
ms.locfileid: "47744958"
---
# <a name="fix-dkim-setup-issues"></a>"DKIM" sąrankos problemų sprendimas

Jei susiduriate su problemomis, įgalinančiomis DKIM jūsų pasirinktiniam domenui, atlikite šiuos veiksmus:

- Daugelis DKIM sąrankos problemų yra susijusios su klaidingais DNS įrašais. Patikrinkite, ar teisingai suformatuotas DKIM CNAME įrašas (**ne** txt įrašas). Daugiau informacijos ieškokite šioje [temoje](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).

- Kai "DKIM" DNS įrašus sukuriate arba naujinate savo domeno DNS išteklių nuomos tarnyboje (paprastai jūsų domenų registratorius), palaukite, kol DNS įrašus išplatins.

- Jei negalite sukurti DKIM DNS įrašus administravimo centre, galite pakeisti \<CustomDomain\> savo pasirinktinio domeno (pvz., contoso.com) ir paleisti šią komandą " [Exchange Online](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell)" "PowerShell": `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true` .
