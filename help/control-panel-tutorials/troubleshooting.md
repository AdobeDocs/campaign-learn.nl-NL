---
title: Problemen met het Configuratiescherm oplossen
description: Leer hoe u problemen met het Configuratiescherm kunt oplossen
feature: 'Configuratiescherm '
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
source-git-commit: 4fc34f56e13c3df5f1c42c24c87a6c7c5caff04b
workflow-type: tm+mt
source-wordcount: '340'
ht-degree: 19%

---

# Probleemoplossing [!UICONTROL Configuratiescherm]

Leer hoe u het Configuratiescherm problemen kunt oplossen.

## Aanmelding en startpagina

### Symptoom: Kan niet aanmelden bij Experience Cloud

**Wat te doen:**
de gebruiker moet van hun IMS Org ID (xxx) de plaats bepalen. De beheerder moet de gebruiker aan het Profiel van het Product &quot;Campagne-xxx-Admins&quot;voor elke instantie toevoegen die zij zouden willen leiden. Als de gebruiker een beheerder van alle instanties is, moeten zij toevoegen als gebruikers.

### Symptoom: De verbindingen in het Huis van de Experience Cloud om tot [!UICONTROL Controlebord] toegang te hebben verschijnen niet voor een gebruiker

**Oorzaak:**
Gebruikers zien de koppelingen pas nadat ze als gebruikers aan de  _campagne-xxx-beheerders/Admin_ voor productprofielen zijn toegevoegd.

**Wat te doen:**
De beheerder moet de gebruiker aan de Campagne-xxx- _Adminsfor van het Profiel van het Product_  toevoegen die zij zouden willen leiden. Als de gebruiker een beheerder van alle instanties is, moeten zij toevoegen als gebruikers.

### Symptoom: Een instantie wordt niet vermeld in [!UICONTROL Configuratiescherm]

**Oorzaak:**
Meest waarschijnlijke gebruiker moet worden toegevoegd als  ** userProduct Profile  _Campaign-xxx-Administrators/_ Adminfor de instantie die mist

**Wat te doen:**
De beheerder moet de gebruiker aan de Campagne-xxx- _Adminsfor van het Profiel van het Product_  toevoegen die zij zouden willen leiden. Als de gebruiker een beheerder van alle instanties is, moeten zij toevoegen als &quot;gebruikers&quot;.

### Nuttige video’s

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*IMS-organisatie-id controleren (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Beheerders toevoegen aan het productprofiel zodat ze het  [!UICONTROL regelpaneel]  kunnen gebruiken (01:03 min)*

### Nuttige documentatie

* [Het Configuratiescherm verkennen](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl)
* [Machtigingen beheren voor het  [!UICONTROL Configuratiescherm]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Verbinding met SFTP-server tot stand brengen (client of API)

Voor verbinding met SFTP-servers is het volgende vereist:

* [!UICONTROL Het ] weergeven van het IP-adres toestaan waarmee u verbinding maakt met de SFTP-server
* Persoonlijke/openbare sleutelparen die bij Adobe Campaign moeten worden geregistreerd
* Als u rechtstreeks verbinding wilt maken met de SFTP-server, hebt u ook SFTP-clientsoftware nodig

### Nuttige documentatie {#helpful-docs}

* [Aanmelden bij uw SFTP-server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
