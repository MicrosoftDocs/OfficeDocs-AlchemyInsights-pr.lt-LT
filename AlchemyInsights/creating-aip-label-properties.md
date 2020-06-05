---
title: AIP etikečių strategijų kūrimas
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "4539"
- "9002266"
ms.openlocfilehash: de7d76564cabb0a5dd1a836984df6b1a63b2b218
ms.sourcegitcommit: 8fdcd2acd31e8a4b9a8a0b91674f397d2f7889c1
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 06/03/2020
ms.locfileid: "44569206"
---
# <a name="creating-aip-label-policies"></a><span data-ttu-id="fc4c0-102">AIP etikečių strategijų kūrimas</span><span class="sxs-lookup"><span data-stu-id="fc4c0-102">Creating AIP Label Policies</span></span>

<span data-ttu-id="fc4c0-103">"Azure Information Protection" (AIP) etiketės gali būti naudojamos su visais duomenimis, kuriuos organizacija paprastai sukuria ir saugo nuo žemiausios asmens duomenų klasifikacijos iki didžiausios labai konfidencialių duomenų klasifikacijos.</span><span class="sxs-lookup"><span data-stu-id="fc4c0-103">Azure Information Protection(AIP) labels can be used with the full range of data that an organization typically creates and stores, from the lowest classification of personal data, to the highest classification of highly confidential data.</span></span> <span data-ttu-id="fc4c0-104">Azure informacijos apsaugos strategijos taikomos Azure informacijos apsaugos (AIP) klasikinis klientas, o ne [AIP vieningosios etikečių kliento](https://docs.microsoft.com/azure/information-protection/rms-client/unifiedlabelingclient-version-release-history).</span><span class="sxs-lookup"><span data-stu-id="fc4c0-104">Azure Information Protection Policies apply to the Azure Information Protection(AIP) classic client and not the  [AIP Unified Labeling client](https://docs.microsoft.com/azure/information-protection/rms-client/unifiedlabelingclient-version-release-history).</span></span> <span data-ttu-id="fc4c0-105">AIP strategijoje galite konfigūruoti kelis elementus, įskaitant parinktis, pvz.:</span><span class="sxs-lookup"><span data-stu-id="fc4c0-105">You can configure multiple elements in an AIP policy, including options like:</span></span>

- <span data-ttu-id="fc4c0-106">Galimybė, kuriai ženklas leis administratoriams arba naudotojams klasifikuoti ir apsaugoti (neprivaloma) dokumentus ir el. laiškus</span><span class="sxs-lookup"><span data-stu-id="fc4c0-106">Option for which label will let administrators or user classify and protection(optional) documents and emails</span></span>
- <span data-ttu-id="fc4c0-107">Galimybė įgalinti klasifikaciją, kai vartotojai įrašo dokumentus ir siunčia el. laiškus</span><span class="sxs-lookup"><span data-stu-id="fc4c0-107">Option to enforce classification when users save documents and send email</span></span>
- <span data-ttu-id="fc4c0-108">Galimybė automatiškai žymėti el. Laišką, atsižvelgiant į jo priedus.</span><span class="sxs-lookup"><span data-stu-id="fc4c0-108">Option to automatically label an email message, based on its attachments.</span></span>
- <span data-ttu-id="fc4c0-109">Galimybė valdyti, ar informacijos apsaugos juosta rodoma "Office" programose</span><span class="sxs-lookup"><span data-stu-id="fc4c0-109">Option to control whether the Information Protection bar is displayed in Office applications</span></span>

<span data-ttu-id="fc4c0-110">Papildomų parinkčių ir informacijos apie Azure informacijos apsaugos strategijos, ieškokite: ["Azure" informacijos apsaugos strategijos apžvalga](https://docs.microsoft.com/azure/information-protection/overview-policy).</span><span class="sxs-lookup"><span data-stu-id="fc4c0-110">For additional options and information on Azure Information Protection policies, see: [Overview of the Azure Information Protection policy](https://docs.microsoft.com/azure/information-protection/overview-policy).</span></span>  

<span data-ttu-id="fc4c0-111">Kitų naudingų išteklių, susijusių su AIP politika, žr.:</span><span class="sxs-lookup"><span data-stu-id="fc4c0-111">For other helpful resources regarding AIP policies, see:</span></span>

- [<span data-ttu-id="fc4c0-112">Vadovėlis: "Azure" informacijos apsaugos strategijos parametrų konfigūravimas ir naujos etiketės kūrimas</span><span class="sxs-lookup"><span data-stu-id="fc4c0-112">Tutorial: Configure Azure Information Protection policy settings and create a new label</span></span>](https://docs.microsoft.com/azure/information-protection/infoprotect-quick-start-tutorial)  
- [<span data-ttu-id="fc4c0-113">"Azure" informacijos apsaugos strategijos konfigūravimas</span><span class="sxs-lookup"><span data-stu-id="fc4c0-113">Configuring the Azure Information Protection policy</span></span>](https://docs.microsoft.com/azure/information-protection/configure-policy)  
- [<span data-ttu-id="fc4c0-114">Jautrumo etikečių ir jų strategijų kūrimas ir konfigūravimas</span><span class="sxs-lookup"><span data-stu-id="fc4c0-114">Create and configure sensitivity labels and their policies</span></span>](https://docs.microsoft.com/microsoft-365/compliance/create-sensitivity-labels)  
- [<span data-ttu-id="fc4c0-115">"How-to" vadovai dažniausiai pasitaikančių scenarijų, kurie naudoja Azure informacijos apsauga</span><span class="sxs-lookup"><span data-stu-id="fc4c0-115">How-to guides for common scenarios that use Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/how-to-guides)  
- [<span data-ttu-id="fc4c0-116">"Azure" informacijos apsaugos dokumentų peržiūra</span><span class="sxs-lookup"><span data-stu-id="fc4c0-116">Review Azure Information Protection documentation</span></span>](https://docs.microsoft.com/azure/information-protection/what-is-information-protection)  
- [<span data-ttu-id="fc4c0-117">"Azure" informacijos apsaugos reikalavimai</span><span class="sxs-lookup"><span data-stu-id="fc4c0-117">Requirements for Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/get-started/requirements)  
- [<span data-ttu-id="fc4c0-118">"Azure" informacijos apsaugos greito pasirengimo darbui pamoka</span><span class="sxs-lookup"><span data-stu-id="fc4c0-118">Quick start tutorial for Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/get-started/infoprotect-quick-start-tutorial)  
- [<span data-ttu-id="fc4c0-119">Atsisiųskite "Azure" informacijos apsaugos klientą</span><span class="sxs-lookup"><span data-stu-id="fc4c0-119">Download Azure Information Protection client</span></span>](https://www.microsoft.com/download/details.aspx?id=53018)