---
title: Validatieworkflows maken
description: Leer hoe u verschillende workflows voor goedkeuringsvalidatie configureert.
feature: Workflows, goedkeuringen
kt: 7991
doc-type: feature video
activity: setup
team: TM
role: Business Practitioner
level: Experienced
source-git-commit: f6bb16306773a4b6ff7aa390a514e9b31fe047d6
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 100%

---


# Validatieworkflows maken

Adobe Campaign biedt verschillende opties voor marketers om leveringscontent, campagnedoel, data-extractie en begrotingsgoedkeuringen te reviewen en te leveren.

In deze tutorial wordt uitgelegd hoe u verschillende workflows voor goedkeuringsvalidatie kunt configureren.

## Vereiste {#prerequisite}

Voordat het marketingteam goedkeuringsstappen kan uitvoeren, moet het team afzonderlijke reviewers definiëren:

* De Adobe Campaign-reviewerrol binnen een goedkeuringsactiviteit kan één reviewer (operator) of een groep reviewers (operatorrol) zijn.
* Om campagneontwikkelaars in staat te stellen om de reviewers als fiatteurs in een campagne of een levering te selecteren, moeten de reviewers en de reviewergroepen in Adobe Campaign door een beheerder worden geconfigureerd.

## Goedkeuringen voor campagnes configureren {#configuring-approvals-for-campaigns}

Als u dezelfde set reviewers voor alle leveringen in uw campagneworkflow hebt, past u de goedkeuringsfunctionaliteit voor de campagne toe door goedkeuringen en reviewers op campagnereniveau in te stellen. De goedkeuringstaken en reviewers worden naar elke leveringsactiviteit van uw workflow verplaatst zodra de workflow wordt uitgevoerd.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Goedkeuringen voor leveringen configureren {#configuring-approvals-for-deliveries}

U kunt goedkeuringen ook instellen op leveringsniveau. Als de stappen voor de goedkeuring van de levering en de reviewers afwijken van de stappen voor de goedkeuring van de campagne, hebben de leveringsinstellingen voorrang op de campagne-instellingen.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Een goedkeuringsactiviteit configfureren {#configuring-an-approval-activity}

In tegenstelling tot de goedkeuring van leveringen of campagnes is het met de goedkeuringsactiviteit mogelijk om een goedkeuringsproces binnen een workflow te maken. Op deze manier kan de doelgerichte selectielogica worden goedgekeurd voordat de levering wordt gestart. Zo nodig is ook goedkeuring op veelvoudige niveaus binnen de workflow mogelijk.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Raadpleeg de [Goedkeuringsdocumentatie](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=nl) voor meer informatie.
