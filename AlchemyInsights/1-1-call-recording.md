---
title: 1:1 skambučio įrašymas
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/18/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002530"
- "7648"
ms.openlocfilehash: 18c68fee514681b2a81c3cfa022c29ce83834f22
ms.sourcegitcommit: 610a5d950cdf488870601762ef52d881e3e22a48
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 05/28/2021
ms.locfileid: "52696966"
---
# <a name="11-call-recording"></a><span data-ttu-id="b67b3-102">1:1 skambučio įrašymas</span><span class="sxs-lookup"><span data-stu-id="b67b3-102">1:1 call recording</span></span>

<span data-ttu-id="b67b3-103">Jei mygtukas **Pradėti** įrašymą yra pilkas 1:1 skambučio metu, turite pakeisti paveikto vartotojo strategijos parametrus.</span><span class="sxs-lookup"><span data-stu-id="b67b3-103">If the **Start Recording** button is grayed out in a 1:1 call, you need to change the policy settings for the impacted user.</span></span>   

<span data-ttu-id="b67b3-104">Nuo 2021 m. gegužės 31 d. pradėsime taikyti naują skambučių Teams *AllowCloudRecordingForCalls.*</span><span class="sxs-lookup"><span data-stu-id="b67b3-104">Beginning May 31, 2021, we'll start enforcing a new Teams Calling Policy *AllowCloudRecordingForCalls*.</span></span> <span data-ttu-id="b67b3-105">Prieš šį keitimą 1:1 skambučio įrašą valdo *"AllowCloudRecording"* Teams susitikimo strategija.</span><span class="sxs-lookup"><span data-stu-id="b67b3-105">Prior to this change, 1:1 call recording is controlled by the *AllowCloudRecording* Teams Meeting Policy.</span></span> <span data-ttu-id="b67b3-106">Šis pakeitimas dokumentuojamas pranešimų centro skelbime: [(atnaujinta) 1:1 Skambučių įrašymo strategijos įvadas](https://portal.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC238796).</span><span class="sxs-lookup"><span data-stu-id="b67b3-106">This change is documented in the Message Center post: [(Updated) 1:1 Call recording policy introduction](https://portal.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC238796).</span></span>  

<span data-ttu-id="b67b3-107">*AllowCloudRecordingForCalls*   skambinimo strategijos parinktis nustatyta **kaip $False pagal** numatytuosius parametrus.</span><span class="sxs-lookup"><span data-stu-id="b67b3-107">*AllowCloudRecordingForCalls* calling policy option is set to **$False** by default.</span></span> <span data-ttu-id="b67b3-108">Jei norite blokuoti visus vartotojus nuo 1:1 skambučių įrašymo, jums nereikia atlikti jokių veiksmų.</span><span class="sxs-lookup"><span data-stu-id="b67b3-108">If you prefer to block all users from recording 1:1 calls, you don't need to take any action.</span></span>  

<span data-ttu-id="b67b3-109">Norėdami įgalinti skambučių įrašymą visiems vartotojams 1:1 skambučiuose, naudokite "Teams PowerShell", kad paleistumėte šią "cmdlet":</span><span class="sxs-lookup"><span data-stu-id="b67b3-109">To enable call recording for all users in 1:1 calls use Teams PowerShell to run the following cmdlet:</span></span> 

<span data-ttu-id="b67b3-110">**Set-CsTeamsCallingPolicy -Identity Global -AllowCloudRecordingForCalls $True**</span><span class="sxs-lookup"><span data-stu-id="b67b3-110">**Set-CsTeamsCallingPolicy -Identity Global -AllowCloudRecordingForCalls $True**</span></span> 

<span data-ttu-id="b67b3-111">Taip pat galite sukurti naują strategiją ir **nustatyti -AllowCloudRecordingForCalls** **$true** priskirti šią strategiją vartotojams.</span><span class="sxs-lookup"><span data-stu-id="b67b3-111">Alternatively, you can create a new policy and set **-AllowCloudRecordingForCalls** to **$true** and assign that policy to your users.</span></span> 

<span data-ttu-id="b67b3-112">Daugiau informacijos žr. [1:1 Skambučių įrašymo strategijos valdikliai yra (beveik!) Čia](https://techcommunity.microsoft.com/t5/microsoft-teams-support/1-1-call-recording-policy-controls-are-almost-here/ba-p/2217668).</span><span class="sxs-lookup"><span data-stu-id="b67b3-112">For more information, see [1:1 Call Recording Policy Controls Are (Almost!) Here](https://techcommunity.microsoft.com/t5/microsoft-teams-support/1-1-call-recording-policy-controls-are-almost-here/ba-p/2217668).</span></span>
