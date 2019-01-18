---
title: Šalinkite triktis naudodami werbowania į Microsoft Intune "Android" įrenginių
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.openlocfilehash: 2f4fc434128ebe7323f0b8c08aec3be82112bbda
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 01/15/2019
ms.locfileid: "28302408"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a>Šalinkite triktis naudodami werbowania į Microsoft Intune "Android" įrenginių

Peržiūrėkite žemiau siekiama išspręsti jūsų problemą dabar ištekliai.
  
Kai kurios Dažnos problemos ir sprendimo veiksmai:
  
 **Prietaisas nėra šifruojami klaida įmonės portale:** Naujesnių versijų "Android", ypač pradedant v7.0, reikalauja paleisties kodą, norėdami įsitikinti, kad jūsų įrenginys yra visiškai iššifruoti. Bendri sprendimai yra įgalinti paleisties pin arba visiškai šifruoti prietaiso. Peržiūrėti [šio dokumento](https://docs.microsoft.com/en-us/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) dėl daugiau informacijos. 
  
 **Įrenginių nesugeba patikrinti su Intune tarnyba arba Rodyti kaip "Nesveiko" Intune administratoriaus konsolėje:** Kai kurios "Samsung" 4.4 ir 5.5 įrenginiai negali tikrinti ir eksploatuoti. Yra 3 galimi siekiant šią problemą: 
  
1. Rankiniu būdu atidaryti Intune įmonės portalo programą, kuri bus automatiškai pradėti įrenginio sinchronizavimą.
    
2. Atnaujinti įrenginio į "Android" 6.0 arba naujesnė.
    
3. Išjungti Samsung Smart Manager valdymo Intune įmonės portalas. Peržiūrėti daugiau informacijos apie šios problemos ir sprendimai [šiame dokumente](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) . 
    
 **Vartotojo licencijos tipas neteisingas** arba **vartotojo vardas nėra atpažįstamas klaida:** vartotojas turi priskirti Intune arba EMS licenciją. Peržiūrėkite šiuos dokumentus priskirti licenciją per: Office administravimo centro arba Azure portalas. 
  
Papildomų išteklių, kurie padės išspręsti jūsų problemą:
  
1. Naudoti [Intune trikčių šalinimo portalas](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) diagnozuoti ir išspręsti bendras registracijos nesėkmių. Peržiūrėti daugiau informacijos [šiame dokumente](https://docs.microsoft.com/en-us/intune/help-desk-operators) . 
    
2. Peržiūrėti [šį dokumentą](https://docs.microsoft.com/en-us/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) bendrosios klaidos, kurios neleis registracijos ir rezoliucijas į kiekvieną sąrašą. 
    
3. [Sužinokite, kaip Registruotis "Android" įrenginius į Microsoft Intune](https://docs.microsoft.com/en-us/intune/android-enroll).
    
