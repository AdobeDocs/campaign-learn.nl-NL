---
title: Aan de slag met pushmeldingen voor Android - Inleiding
description: Deze zelfstudie begeleidt u door de stappen die nodig zijn voor het verzenden van pushberichten van Adobe Campaign en het ontvangen van deze meldingen in uw Android™-app.
feature: Push
kt: 6438
doc-type: article
activity: setup
team: TM
role: Administrator, Developer
level: Experienced
source-git-commit: 39bed2fe5fbe19101a9684b29d73f61026ad77b2
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 41%

---

# Aan de slag met pushmeldingen voor Android - Inleiding

Met Adobe Campaign kunt u gepersonaliseerde en gesegmenteerde [!DNL push]-meldingen verzenden naar mobiele [!DNL iOS]- en [!DNL Android™]-apparaten. In deze zelfstudie worden de stappen besproken die nodig zijn om [!DNL push]-berichten van Adobe Campaign naar een [!DNL Android™]-app te verzenden.

## Vereisten

Voordat u kunt beginnen, moet u over het volgende beschikken:

1) **Android™ Mobile-toepassing**

   In deze tutorial worden niet de gedetailleerde stappen behandeld die nodig zijn om de mobiele applicatie in te stellen. U moet een **[!DNL Android™]mobiele toepassing met [!DNL Campaign SDK] geïntegreerd** hebben.

   U vindt een gedetailleerde beschrijving van de vereiste stappen in de productdocumentatie:

   [De Campaign-SDK integreren in de mobiele applicatie](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=nl)

2) **[!DNL Mobile App channel]-pakket geïnstalleerd**

   Het [!DNL Mobile App channel] pakket moet op uw [!DNL Campaign] instantie worden geïnstalleerd. In de volgende video wordt uitgelegd hoe u kunt controleren of het [!DNL Mobile App channel] op uw installatie is geïnstalleerd en, indien dit niet het geval is, hoe u dit installeert.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Overzicht van tutorial

Het doel is een gepersonaliseerde promotiekennisgeving [!DNL push] te verzenden aan de abonnees van de [!DNL Neotrip] [!DNL Android™] mobiele app. De [!DNL Neotrip]-toepassing wordt geconfigureerd met [!DNL Campaign SDK] en [!DNL Mobile App channel] wordt geactiveerd op de [!DNL Campaign]-instantie.

De volgende configuratiestappen zijn vereist:

### Stap 1: Het schema voor app-abonnementen voor het personaliseren van [!DNL push]-meldingen uitbreiden

Als u de [!DNL push]-melding wilt aanpassen, moet u eerst [het schema van het app-abonnement uitbreiden](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md). THis staat het systeem toe om de verpersoonlijkingswaarden op te slaan die van app worden ontvangen wanneer de gebruiker aan de dienst abonneert.

### Stap 2: De Android™-service configureren en de mobiele toepassing maken in Campagne

Vervolgens [moet de Android™-service configuraties zijn en moet de mobiele toepassing worden gemaakt in Campagne](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md). In deze stap wordt de [!DNL Neotrip]-toepassing gedefinieerd als het doel voor de pushmelding.

### Stap 3: De pushmelding configureren en verzenden

Nu is de pushmelding gereed om [geconfigureerd en verzonden](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md) te zijn.

## Tutorial starten

Stap 1: [Het schema voor app-abonnementen uitbreiden](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)
