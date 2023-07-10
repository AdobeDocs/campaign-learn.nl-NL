---
title: Herhalende en doorlopende e-mailleveringen maken
description: Leer hoe u een terugkerende, continue levering instelt en begrijp de verschillen tussen de twee benaderingen.
feature: Workflows
jira: KT-7982
thumbnail: 342637.jpg
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 469aecd7-4774-42c6-b07f-82792dfdc9c2
source-git-commit: 05b49ca012d0d505b117a2fb6b12ff41b51be63e
workflow-type: tm+mt
source-wordcount: '232'
ht-degree: 94%

---

# Herhalende en doorlopende e-mailleveringen maken

In deze tutorial wordt uitgelegd hoe u een terugkerende en continue levering instelt en wat de verschillen tussen de twee benaderingen zijn.

## Terugkerende en doorlopende leveringtracking {#recurring-and-continuous-delivery-tracking}

De terugkomende en ononderbroken leveringen verschillen in de manier waarop contactgegevens worden beheerd:

* Met de **doorlopende levering** kunt u nieuwe ontvangers toevoegen aan een bestaande levering en voorkomt u dat u telkens een levering moet maken wanneer een nieuwe ontvanger wordt toegevoegd. U kunt de creative rechtstreeks bijwerken in de campagneworkflow en deze werkt de sjabloon bij in de bronmap voor de leveringssjabloon.

  Een ononderbroken levering creëert een ENKELE levering en leveringslogboeken (broadLog), en er worden bij elke uitvoering trackinglogboeken toegevoegd die verwijzen naar die ene levering.

![Ononderbroken levering](/help/assets/delivery_continuous.jpg)

* Een **terugkerende levering** leidt tot een leveringsversie telkens als deze wordt uitgevoerd. Als de workflow bijvoorbeeld eenmaal per week wordt uitgevoerd, levert dat na één jaar 52 leveringen op. Het betekent ook dat het brede logboek en de trackinglogboeken per leveringsversie gescheiden zijn.

![Terugkerende levering](/help/assets/delivery_recurring.jpg)

## Een terugkerende levering instellen {#how-to-set-up-a-recurring-delivery}

In de video wordt uitgelegd hoe u een terugkerende levering en een planneractiviteit configureert.

>[!VIDEO](https://video.tv.adobe.com/v/342638?quality=12&learn=on)

## Een doorlopende levering instellen {#how-to-set-up-a-continuous-delivery}

Deze video laat zien hoe u een doorlopende levering configureert met een stapsgewijze query.

>[!VIDEO](https://video.tv.adobe.com/v/342637?quality=12&learn=on)
