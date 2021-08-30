---
title: Problemen met het configuratiescherm oplossen
description: Ontdek hoe u problemen met het configuratiescherm kunt oplossen
feature: 'Configuratiescherm '
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
source-git-commit: 4fc34f56e13c3df5f1c42c24c87a6c7c5caff04b
workflow-type: ht
source-wordcount: '340'
ht-degree: 100%

---

# Problemen met het [!UICONTROL Configuratiescherm] oplossen

Ontdek hoe u problemen met het configuratiescherm kunt oplossen.

## Aanmelding en startpagina

### Probleem: kan niet aanmelden bij Experience Cloud

**Wat moet u doen:**
De gebruiker moet de IMS-organisatie-id (xxx) zoeken. De beheerder moet de gebruiker toevoegen aan het productprofiel ‘Campaign-xxx-Admins’ voor elke versie die deze wil beheren. Als de gebruiker een beheerder van alle versies is, moet deze ook zichzelf toevoegen als gebruiker.

### Probleem: koppelingen in Experience Cloud Home voor toegang tot het [!UICONTROL Configuratiescherm] worden niet weergegeven voor een gebruiker

**Oorzaak:**
Gebruikers zien de koppelingen pas wanneer ze als gebruikers zijn toegevoegd aan het productprofiel _Campaign-xxx-Administrators/Admin_.

**Wat moet u doen:**
De beheerder moet de gebruiker toevoegen aan het productprofiel _Campaign-xxx-Admins_ voor elke versie die deze wil beheren. Als de gebruiker een beheerder van alle versies is, moet deze ook zichzelf toevoegen als gebruiker.

### Probleem: een versie wordt niet vermeld in het [!UICONTROL Configuratiescherm]

**Oorzaak:**
Waarschijnlijk moet de gebruiker worden toegevoegd als *gebruiker* voor het productprofiel _Campaign-xxx-Administrators/Admin_ voor de ontbrekende versie

**Wat moet u doen:**
De beheerder moet de gebruiker toevoegen aan het productprofiel _Campaign-xxx-Admins_ voor elke versie die deze wil beheren. Als de gebruiker een beheerder van alle versies is, moet deze ook zichzelf toevoegen als &#39;gebruiker&#39;.

### Nuttige video’s

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*IMS-organisatie-id controleren (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Een beheerder toevoegen aan de productprofielbeheerders om het [!UICONTROL Configuratiescherm] te kunnen gebruiken (1,03 min)*

### Nuttige documentatie

* [Het Configuratiescherm verkennen](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl)
* [Machtigingen om het [!UICONTROL Configuratiescherm] te beheren](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl)

## Verbinding met SFTP-server tot stand brengen (client of API)

Voor verbinding met SFTP-servers is het volgende vereist:

* [!UICONTROL Lijst met gewenste] IP-adressen vanwaar u verbinding maakt met de SFTP-server
* Persoonlijk/openbaar sleutelpaar dat bij Adobe Campaign moet zijn geregistreerd
* Als u rechtstreeks verbinding maakt met de SFTP-server, hebt u ook SFTP-clientsoftware nodig

### Nuttige documentatie {#helpful-docs}

* [Aanmelden bij uw SFTP-server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl)
