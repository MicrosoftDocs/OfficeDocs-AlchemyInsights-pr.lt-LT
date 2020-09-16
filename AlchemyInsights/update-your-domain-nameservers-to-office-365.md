---
title: Domeno vardų serverių atnaujinimas į „Microsoft“
ms.author: pebaum
author: CrystalThomasMS
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 5d38b331-a0e8-4937-8bda-4f8f715e1976
ms.custom:
- "6"
- "14"
ms.openlocfilehash: 7322fa640f6d043f057c8b7a5e06a18dcd10eec5
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 09/14/2020
ms.locfileid: "47734919"
---
# <a name="update-your-domain-nameservers-to-point-to-microsoft"></a><span data-ttu-id="3d776-102">Domeno vardų serverių atnaujinimas į „Microsoft“</span><span class="sxs-lookup"><span data-stu-id="3d776-102">Update your domain nameservers to point to Microsoft</span></span>

<span data-ttu-id="3d776-103">Pastaba. Vardų serverių pakeitimų išplatinimas kartais gali trukti iki 48 valandų.</span><span class="sxs-lookup"><span data-stu-id="3d776-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="3d776-104">Norėdami nustatyti domeną su "Microsoft", registratoriaus vardų serveriai turi būti atnaujinti.</span><span class="sxs-lookup"><span data-stu-id="3d776-104">To set up your domain with Microsoft, the nameservers at your registrar need to be updated.</span></span> <span data-ttu-id="3d776-105">Sukurkite arba redaguokite vardų serverio įrašus domeno registratoriaus svetainėje.</span><span class="sxs-lookup"><span data-stu-id="3d776-105">Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="3d776-106">Eikite į domeno registratoriaus svetainę ir raskite sritį, kurioje galima redaguoti domeno vardų serverius.</span><span class="sxs-lookup"><span data-stu-id="3d776-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>

2. <span data-ttu-id="3d776-107">Sukurkite arba redaguokite du vardų serverio įrašus, kad jie atitiktų šias reikšmes:</span><span class="sxs-lookup"><span data-stu-id="3d776-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="3d776-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="3d776-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="3d776-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="3d776-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="3d776-110">Įrašyti pakeitimus.</span><span class="sxs-lookup"><span data-stu-id="3d776-110">Save changes.</span></span>

<span data-ttu-id="3d776-111">Šiame straipsnyje taip pat galite ieškoti išsamių instrukcijų: [vardų serverių keitimas norint nustatyti "Microsoft 365" su bet kuriuo domenų registratoriumi](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span><span class="sxs-lookup"><span data-stu-id="3d776-111">You can also find detailed instructions in this article: [Change nameservers to set up Microsoft 365 with any domain registrar](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span></span>
  