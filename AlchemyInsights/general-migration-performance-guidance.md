---
title: Bendrosios perkėlimo našumo rekomendacijos
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "3179"
ms.openlocfilehash: 10a0069c41d2e5128b2592425d815364a83b730f
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932486"
---
# <a name="general-migration-performance-guidance"></a><span data-ttu-id="d1f8b-102">Bendrosios perkėlimo našumo rekomendacijos</span><span class="sxs-lookup"><span data-stu-id="d1f8b-102">General migration performance guidance</span></span>

<span data-ttu-id="d1f8b-103">**Svarbu**: dauguma „SharePoint Online“ ir „OneDrive“ klientų naudoja verslui svarbias taikomąsias programas, lyginant su fone veikiančia tarnyba.</span><span class="sxs-lookup"><span data-stu-id="d1f8b-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="d1f8b-104">Tai apima turinio perkėlimą, duomenų praradimo prevenciją (DLP) ir atsarginio kopijavimo sprendimus.</span><span class="sxs-lookup"><span data-stu-id="d1f8b-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="d1f8b-105">Šiais precedento neturinčiais laikais imamės veiksmų, kad užtikrintume, jog „SharePoint Online“ ir „OneDrive“ tarnybos išliktų lengvai prieinamos ir patikimos jūsų vartotojams, kurie nuotolinio darbo scenarijuose priklauso nuo tarnybos labiau nei kada nors anksčiau.</span><span class="sxs-lookup"><span data-stu-id="d1f8b-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="d1f8b-106">Siekdami šio tikslo, pritaikėme griežtesnius apribojimus fone veikiančioms programoms (perkėlimo, DLP ir atsarginio kopijavimo sprendimų) šiokiadienių dienos valandomis.</span><span class="sxs-lookup"><span data-stu-id="d1f8b-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="d1f8b-107">Turėtumėte tikėtis, kad tuo metu šių programų pralaidumas bus labai apribotas.</span><span class="sxs-lookup"><span data-stu-id="d1f8b-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="d1f8b-108">Tačiau vakarais ir savaitgalio valandomis tame regione tarnyba bus pasirengusi apdoroti žymiai didesnį kiekį užklausų iš fone veikiančių programų.</span><span class="sxs-lookup"><span data-stu-id="d1f8b-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="d1f8b-109">**Perkėlimo našumo rekomendacijos**</span><span class="sxs-lookup"><span data-stu-id="d1f8b-109">**Migration performance guidance**</span></span>

<span data-ttu-id="d1f8b-110">Perkėlimo našumui įtakos gali turėti tinklo infrastruktūra, failo dydis, perkėlimo laikas ir ribojimas.</span><span class="sxs-lookup"><span data-stu-id="d1f8b-110">Migration performance can be impacted by network infrastructure, file size, migration time, and throttling.</span></span> <span data-ttu-id="d1f8b-111">Tai suprasdami, galėsite lengviau planuoti ir maksimaliai padidinti perkėlimo efektyvumą.</span><span class="sxs-lookup"><span data-stu-id="d1f8b-111">Understanding these will help you plan and maximize the efficiency of your migration.</span></span>

- [<span data-ttu-id="d1f8b-112">Bendrosios perkėlimo našumo rekomendacijos</span><span class="sxs-lookup"><span data-stu-id="d1f8b-112">General migration performance guidance</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)