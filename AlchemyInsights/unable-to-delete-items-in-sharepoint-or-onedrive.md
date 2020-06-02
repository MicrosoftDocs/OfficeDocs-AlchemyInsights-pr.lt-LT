---
title: Neįmanoma panaikinti elementų "SharePoint" arba "OneDrive"
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: 8647b65c52a782ca48ca58bb2700556db528796b
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511984"
---
# <a name="unable-to-delete-items"></a>Neįmanoma panaikinti elementų

Saugojimo strategijos gali sukelti tai, jums reikia išjungti arba pašalinti atitinkamą sulaikymą, kuris sukelia šią problemą. Pašalinus saugojimo strategiją arba sulaikymą, pakeitimas gali įsigalioti iki 24 valandų. Įsitikinkite, kad elemente nėra [saugojimo strategijos](https://docs.microsoft.com/microsoft-365/compliance/retention-policies) nustatymo.

Svetainė galėjo viršyti saugyklos limitą, padidinti [svetainės kvotą](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) ir panaikinti elementą.

Įsitikinkite, kad elementas [nepaimtas](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) ir užrakintas kitam vartotojui.

Galiausiai administratoriai gali naudoti [SharePoint modelius ir praktiką](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP), kuriame yra "PowerShell" komandų biblioteka, leidžianti atlikti sudėtingus valdymo veiksmus, pvz., priverstinai naikinant užsispyrusius elementus.
- [Šalinti PNP failą](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Šalinti PNP aplanką](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Šalinti PNP sąrašo elementą](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Šalinti PNP sąrašą](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Šalinti PNP lauką (stulpelį)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)