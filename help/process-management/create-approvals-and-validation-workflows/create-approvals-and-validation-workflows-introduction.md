---
title: Goedkeuring- en validatieworkflows maken - Inleiding
description: Leer hoe u verschillende workflows voor goedkeuringsvalidatie configureert.
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: 806ecfd0c9377b82eef68e1f9499becfe67704eb
workflow-type: tm+mt
source-wordcount: '262'
ht-degree: 64%

---

# Goedkeuring- en validatieworkflows maken - Inleiding

Adobe Campaign biedt verschillende opties voor marketers om leveringscontent, campagnedoel, data-extractie en begrotingsgoedkeuringen te reviewen en te leveren. Leer hoe u [goedkeuringen beheren](/help/process-management/create-approvals-and-validation-workflows/manage-approvals.md).

## Vereiste {#prerequisite}

Voordat het marketingteam goedkeuringsstappen kan uitvoeren, moet het team afzonderlijke reviewers definiëren:

* De Adobe Campaign-reviewerrol binnen een goedkeuringsactiviteit kan één reviewer (operator) of een groep reviewers (operatorrol) zijn.
* Om campagneontwikkelaars in staat te stellen om de reviewers als fiatteurs in een campagne of een levering te selecteren, moeten de reviewers en de reviewergroepen in Adobe Campaign door een beheerder worden geconfigureerd.

## Goedkeuringen configureren {#configuring-approvals}

1. [Goedkeuringen voor campagnes configureren](/help/process-management/create-validation-workflows/configure-approvals-for-campaigns.md): Als u dezelfde set controleurs voor alle leveringen in uw campagneworkflow hebt, past u de goedkeuringsfunctionaliteit voor de campagne toe door goedkeuringen en controleurs op campagnereniveau in te stellen. De goedkeuringstaken en reviewers worden naar elke leveringsactiviteit van uw workflow verplaatst zodra de workflow wordt uitgevoerd.
2. [Goedkeuringen voor leveringen configureren](/help/process-management/create-validation-workflows/configure-approvals-for-deliveries.md): U kunt goedkeuringen ook instellen op leveringsniveau. Als de stappen voor de goedkeuring van de levering en de reviewers afwijken van de stappen voor de goedkeuring van de campagne, hebben de leveringsinstellingen voorrang op de campagne-instellingen.
3. [Een goedkeuringsproces maken in een workflow](/help/process-management/create-validation-workflows/create-approval-process-in-a-workflow.md): Met de goedkeuringsactiviteit kan een goedkeuringsproces worden gemaakt binnen een workflow. Op deze manier kan de doelgerichte selectielogica worden goedgekeurd voordat de levering wordt gestart. Zo nodig is ook goedkeuring op veelvoudige niveaus binnen de workflow mogelijk.

Raadpleeg voor meer informatie de [documentatie](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=nl).
