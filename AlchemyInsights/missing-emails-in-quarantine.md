---
title: Sulaikyti trūkstami el. laiškai
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5668"
- "9002625"
ms.openlocfilehash: 563f76f624f428a46894268b478cf05eb757b497
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52539832"
---
# <a name="missing-emails-in-quarantine"></a><span data-ttu-id="ab59e-102">Sulaikyti trūksta el. laiškų"</span><span class="sxs-lookup"><span data-stu-id="ab59e-102">Missing emails in quarantine"</span></span>

<span data-ttu-id="ab59e-103">Administratoriai gali [peržiūrėti, išleisti arba panaikinti šiuos pranešimus.](/microsoft-365/security/office-365-security/manage-quarantined-messages-and-files)</span><span class="sxs-lookup"><span data-stu-id="ab59e-103">Administrators can [view, release, or delete these messages.](/microsoft-365/security/office-365-security/manage-quarantined-messages-and-files)</span></span>

<span data-ttu-id="ab59e-104">Norėdami atidaryti saugos & centrą, eikite į [https://protection.office.com](https://protection.office.com/) .</span><span class="sxs-lookup"><span data-stu-id="ab59e-104">To open the Security & Compliance Center, go to [https://protection.office.com](https://protection.office.com/).</span></span> <span data-ttu-id="ab59e-105">Norėdami atidaryti sulaikymo puslapį tiesiogiai, eikite į [https://protection.office.com/quarantine](https://protection.office.com/quarantine) .</span><span class="sxs-lookup"><span data-stu-id="ab59e-105">To open the Quarantine page directly, go to [https://protection.office.com/quarantine](https://protection.office.com/quarantine).</span></span>  

<span data-ttu-id="ab59e-106">Galite ieškoti pagal šias reikšmes:</span><span class="sxs-lookup"><span data-stu-id="ab59e-106">You can search by the following values:</span></span>  

- <span data-ttu-id="ab59e-107">**Pranešimo ID**: visuotinai unikalus pranešimo identifikatorius.</span><span class="sxs-lookup"><span data-stu-id="ab59e-107">**Message ID**: The globally unique identifier of the message.</span></span> <span data-ttu-id="ab59e-108">Jei sąraše pasirinksite pranešimą, rodomame išskridimo  srityje Išsami informacija bus rodoma pranešimo **ID** reikšmė.</span><span class="sxs-lookup"><span data-stu-id="ab59e-108">If you select a message in the list, the  **Message ID**  value appears in the  **Details**  flyout pane that appears.</span></span> <span data-ttu-id="ab59e-109">Administratoriai gali naudoti [laiškų sekimą,](/microsoft-365/security/office-365-security/message-trace-scc) kad rastų laiškus ir jų atitinkamas pranešimo ID reikšmes.</span><span class="sxs-lookup"><span data-stu-id="ab59e-109">Admins can use [message trace](/microsoft-365/security/office-365-security/message-trace-scc) to find messages and their corresponding Message ID values.</span></span>
- <span data-ttu-id="ab59e-110">**Siuntėjo el.** pašto adresas: vieno siuntėjo el. pašto adresas.</span><span class="sxs-lookup"><span data-stu-id="ab59e-110">**Sender email address**: A single sender's email address.</span></span>
- <span data-ttu-id="ab59e-111">**Gavėjo el.** pašto adresas: vieno gavėjo el. pašto adresas.</span><span class="sxs-lookup"><span data-stu-id="ab59e-111">**Recipient email address**: A single recipient's email address.</span></span>
- <span data-ttu-id="ab59e-112">**Tema**: naudokite visą laiško temą.</span><span class="sxs-lookup"><span data-stu-id="ab59e-112">**Subject**: Use the entire subject of the message.</span></span> <span data-ttu-id="ab59e-113">Ieškai skiriamos ne abc nuo abc.</span><span class="sxs-lookup"><span data-stu-id="ab59e-113">The search is not case-sensitive.</span></span>

<span data-ttu-id="ab59e-114">Įvedėte ieškos kriterijus, spustelėkite mygtuką ![ Atnaujinti, ](/microsoft-365/media/scc-quarantine-refresh.png?view=o365-worldwide) **kad filtruokite** rezultatus.</span><span class="sxs-lookup"><span data-stu-id="ab59e-114">After you've entered the search criteria, click ![Refresh button](/microsoft-365/media/scc-quarantine-refresh.png?view=o365-worldwide) **Refresh** to filter the results.</span></span>

<span data-ttu-id="ab59e-115">Cmdlet, kurią naudojate laiškams ir failams sulaikyti peržiūrėti ir tvarkyti, yra:</span><span class="sxs-lookup"><span data-stu-id="ab59e-115">The cmdlets you use to view and manages messages and files in quarantine are:</span></span>
- [<span data-ttu-id="ab59e-116">Delete-QuarantineMessage</span><span class="sxs-lookup"><span data-stu-id="ab59e-116">Delete-QuarantineMessage</span></span>](/powershell/module/exchange/delete-quarantinemessage)
- [<span data-ttu-id="ab59e-117">Export-QuarantineMessage</span><span class="sxs-lookup"><span data-stu-id="ab59e-117">Export-QuarantineMessage</span></span>](/powershell/module/exchange/export-quarantinemessage)
- [<span data-ttu-id="ab59e-118">Get-QuarantineMessage</span><span class="sxs-lookup"><span data-stu-id="ab59e-118">Get-QuarantineMessage</span></span>](/powershell/module/exchange/get-quarantinemessage)
- <span data-ttu-id="ab59e-119">[Preview-QuarantineMessage](/powershell/module/exchange/preview-quarantinemessage): Atkreipkite dėmesį, kad ši "cmdlet" skirta tik laiškams, o ne kenkėjiškų programų failams iš "Microsoft" sargybos, skirtai "Office 365", skirtai "SharePoint Online", ""OneDrive" verslui" arba "Teams".</span><span class="sxs-lookup"><span data-stu-id="ab59e-119">[Preview-QuarantineMessage](/powershell/module/exchange/preview-quarantinemessage): Note that this cmdlet is only for messages, not malware files from Microsoft Defender for Office 365 for SharePoint Online, OneDrive for Business, or Teams.</span></span>
- [<span data-ttu-id="ab59e-120">Release-QuarantineMessage</span><span class="sxs-lookup"><span data-stu-id="ab59e-120">Release-QuarantineMessage</span></span>](/powershell/module/exchange/release-quarantinemessage)