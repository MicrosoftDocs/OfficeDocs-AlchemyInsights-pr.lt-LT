---
title: "\"Office\" taikomųjų programų naujinimo kanalų keitimas"
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/27/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1740"
- "9000140"
ms.openlocfilehash: 4939682a6ca95c4f5475ee6aedea48c9ce83df7f
ms.sourcegitcommit: b10cea11b4975354b91193327b58aa4740d34833
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 07/28/2020
ms.locfileid: "45439392"
---
# <a name="change-update-channels-for-office-apps"></a><span data-ttu-id="1d2c4-102">"Office" taikomųjų programų naujinimo kanalų keitimas</span><span class="sxs-lookup"><span data-stu-id="1d2c4-102">Change update channels for Office apps</span></span>

<span data-ttu-id="1d2c4-103">Norėdami pasirinkti norimą naujinimo kanalą, naudokite naujas "Office" diegimo programas, tada įdiekite (arba įdiekite iš naujo) "Office" programas.</span><span class="sxs-lookup"><span data-stu-id="1d2c4-103">For new Office installations, use Office Software Download Settings to select the desired update channel, and then install (or re-install) Office apps.</span></span> <span data-ttu-id="1d2c4-104">Daugiau informacijos rasite [Programinės įrangos atsisiuntimo parametrų valdymas "Office 365".](https://docs.microsoft.com/deployoffice/manage-software-download-settings-office-365)</span><span class="sxs-lookup"><span data-stu-id="1d2c4-104">For more info, see [Manage software download settings in Office 365](https://docs.microsoft.com/deployoffice/manage-software-download-settings-office-365).</span></span> 

<span data-ttu-id="1d2c4-105">**Pastaba** Naujinimo kanalas, pasirinktas naudojant "Office" programinės įrangos atsisiuntimo parametrus, taikomas visiems vartotojams, atliekantiems naujus diegimus naudojant O365 portalą.</span><span class="sxs-lookup"><span data-stu-id="1d2c4-105">**Note** The update channel selected using the Office Software Download Settings applies to all users performing new installations using the O365 portal.</span></span> <span data-ttu-id="1d2c4-106">Daugiau informacijos rasite ["Microsoft 365" arba "Office 2019" atsisiuntimas ir diegimas arba diegimas iš naujo asmeniniame arba "Mac" kompiuteryje](https://support.microsoft.com/office/download-and-install-or-reinstall-microsoft-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658).</span><span class="sxs-lookup"><span data-stu-id="1d2c4-106">For more info, see [Download and install or reinstall Microsoft 365 or Office 2019 on a PC or Mac](https://support.microsoft.com/office/download-and-install-or-reinstall-microsoft-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658).</span></span>   

<span data-ttu-id="1d2c4-107">Esamų "Office" įrenginių, naudokite Office diegimo įrankis (ODT) pereiti į kitą naujinimo kanalą:</span><span class="sxs-lookup"><span data-stu-id="1d2c4-107">For existing Office installations, use the Office Deployment Tool (ODT) to switch to a different update channel:</span></span>  

1. <span data-ttu-id="1d2c4-108">Atsisiųskite naujausią "Office" diegimo įrankį (setup.exe) iš ["Microsoft" atsisiuntimo centro](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="1d2c4-108">Download the latest version of the Office Deployment Tool (setup.exe) from the [Microsoft Download Center](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
2. <span data-ttu-id="1d2c4-109">Nustatykite kanalo, į kurį norite perjungti, pavadinimą.</span><span class="sxs-lookup"><span data-stu-id="1d2c4-109">Identify the name of the channel that you want to switch to.</span></span> <span data-ttu-id="1d2c4-110">Daugiau informacijos ieškokite ["Office" diegimo įrankio konfigūravimo parinktys](https://docs.microsoft.com/DeployOffice/configuration-options-for-the-office-2016-deployment-tool#channel-attribute-part-of-add-element).</span><span class="sxs-lookup"><span data-stu-id="1d2c4-110">For more info, see [Configuration options for the Office Deployment Tool](https://docs.microsoft.com/DeployOffice/configuration-options-for-the-office-2016-deployment-tool#channel-attribute-part-of-add-element).</span></span>
3. <span data-ttu-id="1d2c4-111">Sukurkite konfigūracijos XML failą, kuriame būtų nurodytas atitinkamas kanalo pavadinimas, pvz., update.xml.</span><span class="sxs-lookup"><span data-stu-id="1d2c4-111">Create a configuration XML file specifying the appropriate channel name, for example, update.xml.</span></span>  
    <span data-ttu-id="1d2c4-112">A.</span><span class="sxs-lookup"><span data-stu-id="1d2c4-112">a.</span></span> <Configuration>  
    <span data-ttu-id="1d2c4-113">B.</span><span class="sxs-lookup"><span data-stu-id="1d2c4-113">b.</span></span> <span data-ttu-id="1d2c4-114"><Atnaujinimai **kanalas = "Kas mėnesį"** /></span><span class="sxs-lookup"><span data-stu-id="1d2c4-114"><Updates **Channel="Monthly"** /></span></span>  
    <span data-ttu-id="1d2c4-115">C.</span><span class="sxs-lookup"><span data-stu-id="1d2c4-115">c.</span></span> </Configuration>
4. <span data-ttu-id="1d2c4-116">Didesnių teisių komandinėje eilutėje pereikite į aplanko vietą, kurioje gyvena setup.exe, ir vykdykite šią komandą:</span><span class="sxs-lookup"><span data-stu-id="1d2c4-116">From an elevated command prompt, switch to the folder location where setup.exe resides and run the following command:</span></span>  
    <span data-ttu-id="1d2c4-117">A.</span><span class="sxs-lookup"><span data-stu-id="1d2c4-117">a.</span></span> <span data-ttu-id="1d2c4-118">setup.exe /configure update.xml</span><span class="sxs-lookup"><span data-stu-id="1d2c4-118">setup.exe /configure update.xml</span></span>
5. <span data-ttu-id="1d2c4-119">Paleiskite "Office" programą (pvz., "Excel"), tada pasirinkite **Failo**  >  **abonementas**.</span><span class="sxs-lookup"><span data-stu-id="1d2c4-119">Start an Office application (such as Excel), and then select **File** > **Account**.</span></span> <span data-ttu-id="1d2c4-120">Sekcijoje Produkto informacija pasirinkite **Naujinti parinktis**  >  **Naujinti dabar**.</span><span class="sxs-lookup"><span data-stu-id="1d2c4-120">In the Product Information section, select **Update Options** > **Update Now**.</span></span>

<span data-ttu-id="1d2c4-121">Jei norite gauti daugiau informacijos, [Sužinokite, kaip perjungti naujinimo kanalus esamų Office Apps](https://support.microsoft.com/help/3185078/how-to-switch-from-semi-annual-channel-to-monthly-channel).</span><span class="sxs-lookup"><span data-stu-id="1d2c4-121">For more information, see [How to switch update channels for existing Office Apps](https://support.microsoft.com/help/3185078/how-to-switch-from-semi-annual-channel-to-monthly-channel).</span></span> 

<span data-ttu-id="1d2c4-122">Perjungti naujinimo kanalus pasirinktos grupės vartotojų arba naudojant konfigūracijos tvarkyklė (SCCM), konfigūruoti naujinimo kanalo parametrą naudojant GPO.</span><span class="sxs-lookup"><span data-stu-id="1d2c4-122">For switching update channels for a selected group of users or by using Configuration Manager (SCCM), configure the Update Channel setting using GPO.</span></span> <span data-ttu-id="1d2c4-123">Daugiau informacijos rasite ["Microsoft 365" programėlių naujinimo kanalų apžvalga](https://docs.microsoft.com/deployoffice/overview-update-channels#group-policy).</span><span class="sxs-lookup"><span data-stu-id="1d2c4-123">For more info, see [Overview of update channels for Microsoft 365 Apps](https://docs.microsoft.com/deployoffice/overview-update-channels#group-policy).</span></span> <span data-ttu-id="1d2c4-124">Norėdami gauti daugiau informacijos, [sužinokite, kaip valdyti "Office 365 ProPlus" kanalus IT specialistams](https://techcommunity.microsoft.com/t5/office-365-blog/how-to-manage-office-365-proplus-channels-for-it-pros/ba-p/795813) ir [tvarkyti "Microsoft 365" programėlių naujinimus naudojant "Microsoft Endpoint Configuration Manager".](https://docs.microsoft.com/deployoffice/manage-microsoft-365-apps-updates-configuration-manager)</span><span class="sxs-lookup"><span data-stu-id="1d2c4-124">For details, see [How to manage Office 365 ProPlus Channels for IT Pros](https://techcommunity.microsoft.com/t5/office-365-blog/how-to-manage-office-365-proplus-channels-for-it-pros/ba-p/795813) and [Manage updates to Microsoft 365 Apps with Microsoft Endpoint Configuration Manager](https://docs.microsoft.com/deployoffice/manage-microsoft-365-apps-updates-configuration-manager).</span></span>