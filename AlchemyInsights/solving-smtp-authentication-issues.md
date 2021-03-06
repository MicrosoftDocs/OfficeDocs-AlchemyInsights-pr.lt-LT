---
title: SMTP autentifikavimo ir trikčių diagnostikos įgalinimas
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
ms.openlocfilehash: 4695a2f111823739c4d87fa2b262a5e64e080955
ms.sourcegitcommit: 2103d706492ad7ee9596344714c0520569ebd6af
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 06/23/2021
ms.locfileid: "53077659"
---
# <a name="enable-smtp-authentication-and-troubleshooting"></a>SMTP autentifikavimo ir trikčių diagnostikos įgalinimas

Jei norite įgalinti pašto dėžutės SMTP autentifikavimą arba gaunate klaidą "Klientas nėra autentifikuotas", "Autentifikavimas nesėkmingas" arba "SmtpClientAuthentication" su kodu 5.7.57 arba 5.7.3 arba 5.7.139, kai bandote perduoti el. paštą autentifikuojant įrenginį arba taikomąją programą su "Microsoft 365", atlikite šiuos tris veiksmus, kad išspręstumėte problemą:

1. Išjunkite ["Azure" saugos numatytąsias](/azure/active-directory/fundamentals/concept-fundamentals-security-defaults) reikšmes, įjungdami **Įjungti saugos numatytąsias reikšmes į** **Ne**.

    a. Prisijunkite prie "Azure" portalo kaip saugos administratorius, sąlyginės prieigos administratorius arba visuotinis administratorius.<BR/>
    b. Raskite "Azure Active Directory" > **Ypatybės**.<BR/>
    c. Pasirinkite **Valdyti saugos numatytąsias reikšmes**.<BR/>
    d. Nustatykite **Įjungti saugos numatytąsias reikšmes kaip** **Ne**.<BR/>
    e. Pasirinkite **Įrašyti**.

2. [Įgalinkite kliento SMTP pateikimą](/exchange/clients-and-mobile-in-exchange-online/authenticated-client-smtp-submission#enable-smtp-auth-for-specific-mailboxes) licencijuotose pašto dėžutėse.

    a. Iš "Microsoft 365" administravimo centras eikite į **Aktyvūs vartotojai** ir pasirinkite vartotoją.<BR/>
    b. Eikite į skirtuką Paštas ir dalyje **El. pašto programos** pasirinkite **Valdyti el. pašto programas**.<BR/>
    d. **Įsitikinkite, kad pažymėta Autentifikuota SMTP** (įjungta).<BR/>
    e. Pasirinkite **Įrašyti keitimus**.<BR/>

3. [Išjunkite kelių dalių autentifikavimą (MFA)](/microsoft-365/admin/security-and-compliance/set-up-multi-factor-authentication#turn-off-legacy-per-user-mfa) licencijuotose pašto dėžutėse.

    a. Eikite į "Microsoft 365" administravimo centras ir kairiajame naršymo meniu pasirinkite Vartotojai  >  **aktyvūs vartotojai**.<BR/>
    b. Pasirinkite **Kelių dalių autentifikavimas**.<BR/>
    c. Pasirinkite vartotoją ir išjunkite **kelių dalių autentifikavimą**.<BR/>
