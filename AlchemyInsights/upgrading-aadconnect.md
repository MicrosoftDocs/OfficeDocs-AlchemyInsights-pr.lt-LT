---
title: 932 atnaujinimas AADConnect
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "932"
- "1300025"
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: 07de6f8df7bfda2060977c7d5bc6a01766bf3c0a
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 06/28/2019
ms.locfileid: "35365912"
---
# <a name="upgrade-azure-ad-connect"></a><span data-ttu-id="a2680-102">Atnaujinti žydros AD prisijungti</span><span class="sxs-lookup"><span data-stu-id="a2680-102">Upgrade Azure AD Connect</span></span>

<span data-ttu-id="a2680-103">Pagal numatytąją reikšmę Automatinis atnaujinimas įgalintas Azure AD Connect, kuris padeda užtikrinti, kad jūs naudojate naujausią versiją.</span><span class="sxs-lookup"><span data-stu-id="a2680-103">By default, automatic upgrade is enabled for Azure AD Connect, which helps to ensure you're running the latest version.</span></span> <span data-ttu-id="a2680-104">Patikrinkite automatinio naujinimo parametrus, naudokite **Get-ADSyncAutoUpgrade** cmdlet "PowerShell" Azure AD ".</span><span class="sxs-lookup"><span data-stu-id="a2680-104">To verify the automatic upgrade settings, use the **Get-ADSyncAutoUpgrade** cmdlet in Azure AD PowerShell.</span></span> <span data-ttu-id="a2680-105">Cmdlet bus grąžinta viena iš šių reikšmių:</span><span class="sxs-lookup"><span data-stu-id="a2680-105">The cmdlet will return one of following values:</span></span>

- <span data-ttu-id="a2680-106">**Įjungta**: Automatinis atnaujinimas įgalintas.</span><span class="sxs-lookup"><span data-stu-id="a2680-106">**Enabled**: Automatic upgrade is enabled.</span></span>

- <span data-ttu-id="a2680-107">**Išjungtas**: Automatinis atnaujinimas yra išjungta.</span><span class="sxs-lookup"><span data-stu-id="a2680-107">**Disabled**: Automatic upgrade is disabled.</span></span>

- <span data-ttu-id="a2680-108">**Pakabinamos**: sistemos nebėra gauti automatinius atnaujinimus.</span><span class="sxs-lookup"><span data-stu-id="a2680-108">**Suspended**: The system is no longer eligible to receive automatic upgrades.</span></span> <span data-ttu-id="a2680-109">Negalima sukonfigūruoti šią reikšmę; nustatė sistema.</span><span class="sxs-lookup"><span data-stu-id="a2680-109">You can't configure this value; it's set by the system.</span></span>

<span data-ttu-id="a2680-110">Daugiau informacijos rasite [Automatinis atnaujinimas](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span><span class="sxs-lookup"><span data-stu-id="a2680-110">For more information, see [Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span></span>

<span data-ttu-id="a2680-111">Norėdami atsisiųsti naujausią Azure AD Connect, eikite į [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span><span class="sxs-lookup"><span data-stu-id="a2680-111">To download the latest version of Azure AD Connect, go to [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span></span>
