---
title: DLP taisyklė mūsų banko sąskaitos numeris ne darbo
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: 6eae9146d33f5fc307085dbf931d57bdbb28b82e
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 01/15/2019
ms.locfileid: "28302402"
---
Ar iškilo problemų su **Duomenų praradimo prevencijos (DLP)** ne darbo turinio su **JAV banko sąskaitos numerį** , naudojant DLP slaptos informacijos tipo O365? Jei taip, įsitikinkite, kad jūsų turinys yra reikalingą informaciją, DLP strategijos ieško kai ji įvertinta. 
  
Pavyzdžiui, **JAV banko sąskaitos numeris** politikos suderintas su 85 % pasikliovimo lygmeniu, toliau yra vertinami ir turi būti nustatytas būtų sukelti taisyklė: 
  
- **[Formatu:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 skaitmenų 
    
- **[Modelis:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 nuosekli skaitmenų seka. 
    
- **[Kontrolinė suma:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, nėra jokių kontrolinė suma 
    
- **[Raiškos:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)** DLP politika yra 75 % tikimybė, kad jis aptiko tokia slaptos informacijos jei per arti 300 simbolių: 
    
  - Reguliarios išraiškos Regex_usa_bank_account_number randa modelis atitinkantis turinys
    
  - Raktinis žodis Keyword_usa_Bank_Account yra nustatyta.
    
    Pavyzdžiui, Šis pavyzdys paskatintų politikos **JAV banko sąskaitos numeris** : Atsiskaitomoji sąskaita 78344011 
    
Norėdami gauti daugiau informacijos apie tai, kas reikalinga **JAV banko sąskaitos numerį** , galima aptikti jūsų turinį, skaitykite kitame skyriuje šiame straipsnyje: [Kas the jautrios informacijos tipus ieškokite JAV banko sąskaitos numeris](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)
  
Naudojant įvairių įmontuota slapta informacija tipo, skaitykite šį straipsnį informacijos apie tai, kas yra reikalingi kitokie: [kas the jautrios informacijos tipus ieškokite](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  
