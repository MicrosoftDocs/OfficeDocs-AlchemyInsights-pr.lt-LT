---
title: Problemos prisijungiant prie "Office" programos
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2559"
ms.openlocfilehash: 5f500ecf1f779fb1be4d257fd050a3ad054087dc
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938280"
---
# <a name="fixing-the-office-apps-your-computers-trusted-platform-module-is-not-functioning-properly-message"></a>Nustatant Office apps "jūsų kompiuterio patikimos platformos modulis veikia netinkamai" pranešimas

Norėdami išspręsti šią klaidą, atlikite šiuos veiksmus:

- Įdiekite naujausius [Windows](https://support.microsoft.com/help/4027667/windows-10-update) ir [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).
- [Aišku Office kredencialus](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) naudodami Windows kredencialų tvarkytuvas.<br/>
    **Pastaba:** 16,0 pasikeitė registro maršrutai Office 2016. (Ex: \Software\Microsoft\Office\16.0\Common\Identity\)
- Pabandykite [vartotojo susigrąžinimo procesas](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) nustatyti patikimos platformos modulio (TPM) gedimai.
- Nustatyti, EnableADAL = 0, atlikite šiuos veiksmus:  
    1. Dešiniuoju pelės mygtuku spustelėkite Windows mygtuką pradėti, pasirinkite **vykdyti**, įveskite **regedit**, ir tada pasirinkite **gerai**.
    2. Pasirinkite **taip** , kad registro rengyklę, kad jūsų įrenginio.
    3. Registro rengyklėje pridėti reikšmę DWORD, **EnableADAL** su parametras **0** pagal HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.

Daugiau informacijos ieškokite [ryšio problemų prisijungdami po Office 2016 statyti 16.0.7967 "Windows 10" naujinimą](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).