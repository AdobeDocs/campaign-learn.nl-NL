---
title: 'Aan de slag met pushmeldingen voor Android: inleiding'
description: Deze tutorial leidt u door de stappen die nodig zijn voor het verzenden van pushmeldingen vanuit Adobe Campaign en het ontvangen van deze meldingen in uw Android™-app.
feature: Push
jira: KT-6438
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noCatalog
exl-id: 91ff4bae-8598-4227-b4c9-4e436ce7400d
source-git-commit: 116a24a8aa123f615e08fa4ebd187b3c4c460ba2
workflow-type: tm+mt
source-wordcount: '319'
ht-degree: 99%

---

# Aan de slag met pushmeldingen voor Android - Inleiding

Met Adobe Campaign kunt u gepersonaliseerde en gesegmenteerde [!DNL push]-meldingen verzenden naar mobiele [!DNL iOS]- en [!DNL Android™]-apparaten. Deze tutorial leidt u door de stappen die nodig zijn voor het verzenden van [!DNL push] meldingen vanuit Adobe Campaign naar een [!DNL Android™]-app.

## Vereisten

Voordat u kunt beginnen hebt u het volgende nodig:

1) **Mobiele Android™-applicatie**

   Deze tutorial behandelt niet de gedetailleerde stappen die nodig zijn om de mobiele applicatie in te stellen. U hebt een **[!DNL Android™]mobiele applicatie met [!DNL Campaign SDK] geïntegreerd** nodig.

   U vindt een gedetailleerde beschrijving van de vereiste stappen in de productdocumentatie:

   [De Campaign-SDK integreren in de mobiele applicatie](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=nl)

2) **[!DNL Mobile App channel]-pakket geïnstalleerd**

   Het [!DNL Mobile App channel]-pakket moet op uw [!DNL Campaign]-versie zijn geïnstalleerd. In de volgende video wordt uitgelegd hoe u kunt controleren of het [!DNL Mobile App channel] op uw installatie is geïnstalleerd en, indien dit niet het geval is, hoe u dit installeert.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12&learn=on){transcript=true}

## Overzicht van tutorial

We willen een gepersonaliseerde [!DNL push]-reclamemelding sturen naar de leden van de mobiele [!DNL Neotrip] [!DNL Android™]-app. De [!DNL Neotrip]-app wordt geconfigureerd met de [!DNL Campaign SDK] en de [!DNL Mobile App channel] wordt geactiveerd in de [!DNL Campaign]-versie.

De volgende configuratiestappen zijn vereist:

### Stap 1: Het schema voor app-abonnementen voor het personaliseren van [!DNL push]-meldingen uitbreiden

Als u de [!DNL push]-melding wilt personaliseren, moet u eerst [het van het app-lidmaatschapsschema uitbreiden](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md). Hierdoor kan het systeem de personalisatiewaarden opslaan die van de app worden ontvangen wanneer de gebruiker zich aanmeldt als lid van de service.

### Stap 2: De Android-service configureren en de mobiele applicatie maken in Campaign

Vervolgens [moet de Android™-service worden geconfigureerd en moet de mobiele applicatie worden gemaakt in Campaign](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md). In deze stap wordt de [!DNL Neotrip]-app gedefinieerd als het doel voor de pushmelding.

### Stap 3: De pushmelding configureren en verzenden

Nu is de pushmelding klaar om [geconfigureerd en verzonden](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md) te worden.

## Tutorial starten

Stap 1: [Het schema voor app-abonnementen uitbreiden](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)
