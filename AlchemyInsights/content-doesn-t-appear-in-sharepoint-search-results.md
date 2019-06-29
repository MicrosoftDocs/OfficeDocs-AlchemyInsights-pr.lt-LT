---
title: Turinys nerodomas SharePoint ieškos rezultatus
ms.author: tlarsen
author: tklarsen
ms.date: 1/8/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "750"
- "5300017"
ms.assetid: 693db84f-2737-4c21-b027-4ab3d121b4a8
ms.openlocfilehash: 8215b0a5cde5adffa3bec37d6699418557f914dd
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 06/28/2019
ms.locfileid: "35363822"
---
# <a name="content-doesnt-appear-in-sharepoint-search-results"></a><span data-ttu-id="1d05c-102">Turinys nerodomas SharePoint ieškos rezultatus</span><span class="sxs-lookup"><span data-stu-id="1d05c-102">Content doesn't appear in SharePoint search results</span></span>

<span data-ttu-id="1d05c-103">Atlikite šiuos trikčių šalinimo veiksmus, kai numatomas turinys nėra rodomi paieškos rezultatuose.</span><span class="sxs-lookup"><span data-stu-id="1d05c-103">Follow these troubleshooting steps when expected content doesn't appear in search results:</span></span>
  
1. <span data-ttu-id="1d05c-104">Patikrinkite, kad **svetainė** , kurioje yra tikėtasi nustatyta, kad turinys būtų rodomas paieškos rezultatuose.</span><span class="sxs-lookup"><span data-stu-id="1d05c-104">Check that the **site** that contains the expected content is set to allow content to appear in search results.</span></span> <span data-ttu-id="1d05c-105">Vykdykite [Rodyti turinį svetainės paieškos rezultatuose](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).</span><span class="sxs-lookup"><span data-stu-id="1d05c-105">Follow the steps in [Show content on a site in search results](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).</span></span>

2. <span data-ttu-id="1d05c-106">Patikrinkite **sąrašą** ar **biblioteką** , kuriame tikėtasi yra nustatytas, kad turinys būtų rodomas paieškos rezultatuose.</span><span class="sxs-lookup"><span data-stu-id="1d05c-106">Check that the **list** or **library** that contains the expected content is set to allow content to appear in search results.</span></span> <span data-ttu-id="1d05c-107">Vykdykite [Rodyti turinį iš sąrašų arba bibliotekų paieškos rezultatuose](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).</span><span class="sxs-lookup"><span data-stu-id="1d05c-107">Follow the steps in [Show content from lists or libraries in search results](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).</span></span>

3. <span data-ttu-id="1d05c-108">Patikrinti, kad dokumento puslapio ar Pasirinktinis puslapio maketas yra paskelbtas kaip tam **didelių versija.**</span><span class="sxs-lookup"><span data-stu-id="1d05c-108">Verify that the page, document, or custom page layout is published as a **Major version.**</span></span> <span data-ttu-id="1d05c-109">Sekite žingsnis 3 [paieškos negrąžina visų rezultatų SharePoint Online](https://go.microsoft.com/fwlink/?linkid=874525).</span><span class="sxs-lookup"><span data-stu-id="1d05c-109">Follow step 3 in [Search doesn't return all results in SharePoint Online](https://go.microsoft.com/fwlink/?linkid=874525).</span></span>

4. <span data-ttu-id="1d05c-110">Patikrinkite, ar vartotojas turi **teises** peržiūrėti turinį.</span><span class="sxs-lookup"><span data-stu-id="1d05c-110">Verify that the user has **permissions** to view the content.</span></span> <span data-ttu-id="1d05c-111">Vykdykite [supratimą teisių lygius programoje "SharePoint"](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="1d05c-111">Follow the steps in [Understanding permission levels in SharePoint](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span></span>
    
5. <span data-ttu-id="1d05c-112">Jei ieškos schemos buvo pakeistas pridedant naujas valdoma ypatybė, redaguodami valdoma ypatybė arba panaikinant valdomą ypatybę, tada prašo nuskaitymo ir iš naujo indeksuoti bus reikalingas.</span><span class="sxs-lookup"><span data-stu-id="1d05c-112">If the search schema has been changed by adding a new managed property, by editing a managed property, or by removing a managed property then requesting a crawl and re-index will be required.</span></span> <span data-ttu-id="1d05c-113">**Iš naujo indeksuoti** pagal šiuos veiksmus [rankiniu būdu prašymą ir iš naujo indeksuodama svetainę, biblioteką ar sąrašo](https://docs.microsoft.com/sharepoint/crawl-site-content)turinio.</span><span class="sxs-lookup"><span data-stu-id="1d05c-113">**Re-index** the content by following the steps in [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/sharepoint/crawl-site-content).</span></span> <span data-ttu-id="1d05c-114">Tai gali šiek tiek užtrukti, palaukite 24 valandas iki patikrinimo rezultatai dar kartą.</span><span class="sxs-lookup"><span data-stu-id="1d05c-114">This might take a while, wait 24 hours before checking the results again.</span></span>

<span data-ttu-id="1d05c-115">Daugiau informacijos ieškokite [turinio svetainėje ieškomumo įgalinimas](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="1d05c-115">For more information, see [Enable content on a site to be searchable](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span></span> 
  
