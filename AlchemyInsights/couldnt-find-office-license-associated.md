---
title: "\"Microsoft 365\" programų taisymas nepavyko aptikti \"Office\" licencijų susijusio pranešimo"
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3421"
- "9001426"
ms.openlocfilehash: bd127d6287b4438f6105a6158abdbd5b964b7e70
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 09/14/2020
ms.locfileid: "47747703"
---
# <a name="fixing-the-microsoft-365-apps-couldnt-find-office-licenses-associated-message"></a>"Microsoft 365" taikomųjų programų taisymas "nepavyko aptikti" Office "licencijų susietųjų"

Gavę šį pranešimą, išbandykite šiuos veiksmus:

1. Patikrinkite užkardos, antivirusinės programinės įrangos ir tarpinio serverio parametrus, kad patvirtintumėte, jog jie neužblokuoja interneto prieigos prie "Microsoft" 365 taikomųjų programų. Peržiūrėkite ["Microsoft" 365 URL ir IP adresų diapazonus](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).
2. Pašalinkite ir iš [naujo priskirkite](https://docs.microsoft.com/microsoft-365/admin/manage/assign-licenses-to-users) susijusio vartotojo "Office" licenciją. 
3. Atidarykite "Office" programą ir [atsijunkite](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) nuo esamų vartotojų paskyrų.
4. Eikite į "Windows" parametrai > **paskyros**  >  **el. paštas & paskyras**ir pašalinkite visas darbo paskyras, išskyrus paveiktą paskyrą.
5. Eikite į "Windows" parametrai > **paskyrų**  >  **prieiga prie darbo arba mokymo įstaigos**ir atjunkite visas darbo paskyras, išskyrus paveiktą paskyrą.
6. Iš naujo nustatykite "Office" aktyvinimo būseną. [Sužinokite, kaip](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state).
7. [Prisijunkite](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) naudodami paveiktą vartotojo paskyrą.

Papildomų trikčių šalinimo sprendimų ieškokite [nelicencijuoto produkto ir aktyvinimo klaidos "Office](https://support.office.com/Article/0d23d3c0-c19c-4b2f-9845-5344fedc4380)".