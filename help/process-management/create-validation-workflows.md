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
ht-degree: 0%

---


# Validatieworkflows maken

Adobe Campaign biedt verschillende opties voor marketers om inhoud, campagnedoel, gegevensextractie en begrotingsgoedkeuringen te beoordelen en te leveren.

In deze zelfstudie wordt uitgelegd hoe u verschillende workflows voor goedkeuringsvalidatie kunt configureren.

## Vereiste {#prerequisite}

Voordat het marketingteam goedkeuringsstappen kan uitvoeren, moet het afzonderlijke controleurs definiëren:

* De Adobe Campaign-revisorrol binnen een goedkeuringsactiviteit kan één revisor (operator) of een groep revisoren (operatorrol) zijn.
* Om campagneontwikkelaars in staat te stellen om de controleurs als fiatteurs in een campagne of een levering te selecteren, moeten de recensenten en de recensentengroepen in Adobe Campaign door een beheerder worden gevormd.

## Goedkeuringen voor campagnes configureren {#configuring-approvals-for-campaigns}

Als u dezelfde set controleurs voor alle leveringen in uw campagneworkflow hebt, past u de goedkeuringsfunctionaliteit voor de campagne toe door goedkeuringen en controleurs op campagnereniveau in te stellen. De goedkeuringstaken en controleurs worden onderdrukt aan elke leveringsactiviteit van uw werkschema zodra het werkschema wordt uitgevoerd.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Goedkeuringen voor leveringen configureren {#configuring-approvals-for-deliveries}

U kunt goedkeuringen ook instellen op leveringsniveau. Als de stappen voor de goedkeuring van de levering en de controleurs afwijken van de stappen voor de goedkeuring van de campagne en de controleurs, hebben de leveringsinstellingen voorrang op de instellingen voor de campagne.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Een goedkeuringsactiviteit {#configuring-an-approval-activity} configureren

In tegenstelling tot de levering of campagnegoedkeuringen, staat de goedkeuringsactiviteit toe om een goedkeuringsproces binnen een werkschema tot stand te brengen. Op deze manier kan de doelgerichte selectielogica worden goedgekeurd voordat de levering wordt gestart. Het staat ook goedkeuring op veelvoudige niveaus binnen het werkschema toe, indien nodig.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Raadpleeg voor meer informatie de [goedkeuringsdocumentatie](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
