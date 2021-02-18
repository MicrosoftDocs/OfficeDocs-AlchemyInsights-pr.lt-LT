---
title: Išorinių parametrų valdymas
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 02/10/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8322"
- "9003227"
ms.openlocfilehash: 7caf46f9988ddbcbb16c0a2751dbda85bd7da34c
ms.sourcegitcommit: 616ae0cbd5769e12ae428e00088840cf05e52b6a
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 02/17/2021
ms.locfileid: "50294315"
---
# <a name="managing-external-settings"></a><span data-ttu-id="d87b4-102">Išorinių parametrų valdymas</span><span class="sxs-lookup"><span data-stu-id="d87b4-102">Managing External Settings</span></span>

<span data-ttu-id="d87b4-103">**Pranešimas**</span><span class="sxs-lookup"><span data-stu-id="d87b4-103">**Announcement**</span></span>

- <span data-ttu-id="d87b4-104">[Žiniatinklio rodinio prisijungimo palaikymo palaikymas iš "Google" nuo sausio 4 d., 2021](https://docs.microsoft.com/azure/active-directory/external-identities/google-federation?WT.mc_id=Portal-Microsoft_Azure_Support#deprecation-of-webview-sign-in-support).</span><span class="sxs-lookup"><span data-stu-id="d87b4-104">[Deprecation of WebView sign-in support from Google starting January 4, 2021](https://docs.microsoft.com/azure/active-directory/external-identities/google-federation?WT.mc_id=Portal-Microsoft_Azure_Support#deprecation-of-webview-sign-in-support).</span></span> <span data-ttu-id="d87b4-105">Patikrinkite, ar jūsų programėlėms įtakos turi "Google" rekomendacijos dėl suderinamumo su tikrinimu</span><span class="sxs-lookup"><span data-stu-id="d87b4-105">Test whether your apps are affected by following Google’s guidance on testing compatibility</span></span>
- <span data-ttu-id="d87b4-106">Įsitikinkite, kad prisijungę prie vartotojų, naudodami "Google" paskyras, naudojate sistemos žiniatinklio rodinį arba sistemos naršyklę</span><span class="sxs-lookup"><span data-stu-id="d87b4-106">Make sure to use the system webview or the system browser when signing in your users with consumer Google accounts</span></span>

<span data-ttu-id="d87b4-107">**Valdyti kvietimo parametrus**</span><span class="sxs-lookup"><span data-stu-id="d87b4-107">**Manage Invitation Settings**</span></span>

<span data-ttu-id="d87b4-108">Įsitikinkite, kad [sukonfigūravote išorinius bendradarbiavimo parametrus](https://docs.microsoft.com/azure/active-directory/external-identities/delegate-invitations?WT.mc_id=Portal-Microsoft_Azure_Support) , kad būtų leidžiama atitinkamiems žmonėms išsiųsti kvietimus.</span><span class="sxs-lookup"><span data-stu-id="d87b4-108">Confirm that you have [configured the external collaboration settings](https://docs.microsoft.com/azure/active-directory/external-identities/delegate-invitations?WT.mc_id=Portal-Microsoft_Azure_Support) to allow the appropriate people to send invitations.</span></span>

<span data-ttu-id="d87b4-109">**Svečio vartotojų prieigos teisių valdymas**</span><span class="sxs-lookup"><span data-stu-id="d87b4-109">**Manage Guest User Access Permissions**</span></span>

1. <span data-ttu-id="d87b4-110">Visuotiniai administratoriai gali valdyti svečio prieigos teises kataloge naudodami "Azure" portalą konfigūravę svečio prieigos teises išoriniame bendradarbiavimo parametrų puslapyje.</span><span class="sxs-lookup"><span data-stu-id="d87b4-110">Global admins can manage guest access permissions in the directory through the Azure portal by configuring the guest access permissions on the External Collaboration Settings page.</span></span> <span data-ttu-id="d87b4-111">[Sužinokite daugiau apie šį parametrą](https://docs.microsoft.com/azure/active-directory/fundamentals/users-default-permissions?WT.mc_id=Portal-Microsoft_Azure_Support).</span><span class="sxs-lookup"><span data-stu-id="d87b4-111">[Learn more about this setting](https://docs.microsoft.com/azure/active-directory/fundamentals/users-default-permissions?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>
2. <span data-ttu-id="d87b4-112">Jei norite, kad jūsų svečiai pasiektų tokias programas kaip "teams" ar "SharePoint", patvirtinkite, kad sukonfigūravote šias taikomąsias programas, kad būtų galima pasiekti svečio prieigą.</span><span class="sxs-lookup"><span data-stu-id="d87b4-112">If you would like your guests to access apps such as Teams or SharePoint, confirm that you've configured those apps to allow guest access.</span></span> <span data-ttu-id="d87b4-113">Sužinokite daugiau apie " [teams" parametrus](https://docs.microsoft.com/microsoftteams/guest-access?WT.mc_id=Portal-Microsoft_Azure_Support) ir " [SharePoint](https://docs.microsoft.com/sharepoint/external-sharing-overview?WT.mc_id=Portal-Microsoft_Azure_Support)".</span><span class="sxs-lookup"><span data-stu-id="d87b4-113">Learn more about the [Teams settings](https://docs.microsoft.com/microsoftteams/guest-access?WT.mc_id=Portal-Microsoft_Azure_Support) and [SharePoint](https://docs.microsoft.com/sharepoint/external-sharing-overview?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>

<span data-ttu-id="d87b4-114">**Kvietimų konfigūravimas:**</span><span class="sxs-lookup"><span data-stu-id="d87b4-114">**Configuring invitations:**</span></span>

- [<span data-ttu-id="d87b4-115">Įgalinti B2B išorinį bendradarbiavimą ir valdyti, kas gali pakviesti svečius</span><span class="sxs-lookup"><span data-stu-id="d87b4-115">Enable B2B external collaboration and manage who can invite guests</span></span>](https://docs.microsoft.com/azure/active-directory/b2b/delegate-invitations?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="d87b4-116">Leisti arba blokuoti kvietimus vartotojams iš konkrečių organizacijų</span><span class="sxs-lookup"><span data-stu-id="d87b4-116">Allow or block invitations to users from specific organizations</span></span>](https://docs.microsoft.com/azure/active-directory/b2b/allow-deny-list?WT.mc_id=Portal-Microsoft_Azure_Support)

<span data-ttu-id="d87b4-117">**Leidžiamų tapatybės teikėjų konfigūravimas:**</span><span class="sxs-lookup"><span data-stu-id="d87b4-117">**Configuring allowed identity providers:**</span></span>

- [<span data-ttu-id="d87b4-118">"Google" federacija</span><span class="sxs-lookup"><span data-stu-id="d87b4-118">Google Federation</span></span>](https://docs.microsoft.com/azure/active-directory/b2b/google-federation?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="d87b4-119">Tiesioginė federacija</span><span class="sxs-lookup"><span data-stu-id="d87b4-119">Direct Federation</span></span>](https://docs.microsoft.com/azure/active-directory/b2b/direct-federation?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="d87b4-120">Vieno laiko prieigos kodo autentifikavimo autentifikavimas</span><span class="sxs-lookup"><span data-stu-id="d87b4-120">Email one-time Passcode Authentication</span></span>](https://docs.microsoft.com/azure/active-directory/b2b/one-time-passcode?WT.mc_id=Portal-Microsoft_Azure_Support)
