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
ms.openlocfilehash: 8cdadf34a059856338d7f40528446b70373465e4
ms.sourcegitcommit: d2108b13acc44e26b65f9a2739cbce9bf98959a5
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 05/28/2021
ms.locfileid: "52702098"
---
# <a name="11-call-recording"></a><span data-ttu-id="0273e-102">1:1 skambučio įrašymas</span><span class="sxs-lookup"><span data-stu-id="0273e-102">1:1 call recording</span></span>

<span data-ttu-id="0273e-103">Jei mygtukas **Pradėti** įrašymą yra pilkas 1:1 skambučio metu, turite pakeisti paveikto vartotojo strategijos parametrus.</span><span class="sxs-lookup"><span data-stu-id="0273e-103">If the **Start Recording** button is grayed out in a 1:1 call, you need to change the policy settings for the impacted user.</span></span> <span data-ttu-id="0273e-104">Norėdami patikrinti strategijos parametrą, paleiskite paveikto vartotojo diagnostiką įvesdami **Diag: Teams 1:1 Call Recording** above.</span><span class="sxs-lookup"><span data-stu-id="0273e-104">To check the policy setting, run the Diagnostic for the impacted user by typing **Diag: Teams 1:1 Call Recording** above.</span></span>     

<span data-ttu-id="0273e-105">Nuo 2021 m. gegužės 31 d. pradėsime taikyti naują skambučių Teams *AllowCloudRecordingForCalls.*</span><span class="sxs-lookup"><span data-stu-id="0273e-105">Beginning May 31, 2021, we'll start enforcing a new Teams Calling Policy *AllowCloudRecordingForCalls*.</span></span> <span data-ttu-id="0273e-106">Prieš šį keitimą 1:1 skambučio įrašą valdo *"AllowCloudRecording"* Teams susitikimo strategija.</span><span class="sxs-lookup"><span data-stu-id="0273e-106">Prior to this change, 1:1 call recording is controlled by the *AllowCloudRecording* Teams Meeting Policy.</span></span> <span data-ttu-id="0273e-107">Šis pakeitimas dokumentuojamas pranešimų centro skelbime: [(atnaujinta) 1:1 Skambučių įrašymo strategijos įvadas](https://portal.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC238796).</span><span class="sxs-lookup"><span data-stu-id="0273e-107">This change is documented in the Message Center post: [(Updated) 1:1 Call recording policy introduction](https://portal.microsoft.com/Adminportal/Home?ref=MessageCenter/:/messages/MC238796).</span></span>  

<span data-ttu-id="0273e-108">*AllowCloudRecordingForCalls*   skambinimo strategijos parinktis nustatyta **kaip $False pagal** numatytuosius parametrus.</span><span class="sxs-lookup"><span data-stu-id="0273e-108">*AllowCloudRecordingForCalls* calling policy option is set to **$False** by default.</span></span> <span data-ttu-id="0273e-109">Jei norite blokuoti visus vartotojus nuo 1:1 skambučių įrašymo, jums nereikia atlikti jokių veiksmų.</span><span class="sxs-lookup"><span data-stu-id="0273e-109">If you prefer to block all users from recording 1:1 calls, you don't need to take any action.</span></span>  

<span data-ttu-id="0273e-110">Norėdami įgalinti skambučių įrašymą visiems vartotojams 1:1 skambučiuose, [naudokite "Teams PowerShell",](/microsoftteams/teams-powershell-install) kad paleistumėte šią "cmdlet":</span><span class="sxs-lookup"><span data-stu-id="0273e-110">To enable call recording for all users in 1:1 calls use [Teams PowerShell](/microsoftteams/teams-powershell-install) to run the following cmdlet:</span></span> 

<span data-ttu-id="0273e-111">**Set-CsTeamsCallingPolicy -Identity Global -AllowCloudRecordingForCalls $True**</span><span class="sxs-lookup"><span data-stu-id="0273e-111">**Set-CsTeamsCallingPolicy -Identity Global -AllowCloudRecordingForCalls $True**</span></span> 

<span data-ttu-id="0273e-112">Taip pat galite sukurti naują strategiją ir **nustatyti -AllowCloudRecordingForCalls** **$true** priskirti šią strategiją vartotojams.</span><span class="sxs-lookup"><span data-stu-id="0273e-112">Alternatively, you can create a new policy and set **-AllowCloudRecordingForCalls** to **$true** and assign that policy to your users.</span></span> 

<span data-ttu-id="0273e-113">Daugiau informacijos žr. [1:1 Skambučių įrašymo strategijos valdikliai yra (beveik!) Čia](https://techcommunity.microsoft.com/t5/microsoft-teams-support/1-1-call-recording-policy-controls-are-almost-here/ba-p/2217668).</span><span class="sxs-lookup"><span data-stu-id="0273e-113">For more information, see [1:1 Call Recording Policy Controls Are (Almost!) Here](https://techcommunity.microsoft.com/t5/microsoft-teams-support/1-1-call-recording-policy-controls-are-almost-here/ba-p/2217668).</span></span>
