---
title: SMTP autentifikavimo problemų sprendimas
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
- "3000003"
- "5652"
ms.openlocfilehash: 2d3f0f6b700c3e4485c9064fbaa4bcc165e92e17
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 04/15/2021
ms.locfileid: "51826423"
---
# <a name="solving-smtp-authentication-issues"></a>SMTP autentifikavimo problemų sprendimas

Jei gaunate 5.7.57 arba 5.7.3 klaidų bandydami siųsti SMTP el. paštą ir autentifikuoti naudodami klientą arba taikomąją programą, yra keletas dalykų, kuriuos turėtumėte patikrinti:

- Autentifikuotas SMTP pateikimas gali būti išjungtas jūsų nuomotoje arba pašto dėžutėje, kurią bandote naudoti (patikrinkite abu parametrus). Norėdami skaityti daugiau, žr. [Autentifikuoto kliento SMTP pateikimo įjungimas arba išjungimas](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/authenticated-client-smtp-submission).

- Patikrinkite, [ar jūsų nuomotojui įgalintos "Azure"](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults) saugos numatytosios funkcijos; jei įgalinta, SMTP autentifikavimas naudojant bazinį autentifikavimą (dar vadinamą senesniu; bus naudojamas vartotojo vardas ir slaptažodis) nepavyks.
