---
title: Een exportworkflow maken (deel 1) - De laatste gewijzigde datum zoeken voor een lijst met ontvangers
description: In dit eerste deel van Create leert een zelfstudie van het Werkschema van de Uitvoer, hoe te om een werkschema tot stand te brengen dat de laatste gewijzigde datum voor een lijst van ontvangers vindt die van een segment van de Experience Platform worden gecreeerd.
feature: Data Import/Export, Workflows
kt: 8162
thumbnail: 336387.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: 6fd70eea-3be7-4589-a608-05b0a8de93a6
source-git-commit: 85a32e0415c02ccfff9a22021ed77872ad726bf7
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---

# Een exportworkflow maken (deel 1) - De laatste gewijzigde datum zoeken voor een lijst met ontvangers

In dit eerste deel van Create leert een zelfstudie van het Werkschema van de Uitvoer, hoe te om een werkschema tot stand te brengen dat de laatste gewijzigde datum voor een lijst van ontvangers vindt die van een segment van de Experience Platform worden gecreeerd.

>[!VIDEO](https://video.tv.adobe.com/v/336387?quality=12)

## Activa

JavaScript voor het instellen van datumbereiken:

```java
 var DEFAULT_LOOKBACK_DAYS = 90;
 vars.OPTION_NAME = "BroadLog_CaptureTime";

 logInfo("=====================");
 logInfo("Starting Execution...");

 // Establish the last and next RunTimes
 var lastRunTime = getOption(vars.OPTION_NAME);
 var nextRunTime = getCurrentDate();

 //To reset and run through DEFAULT_LOOKBACK, uncomment the following line.
 //lastRunTime = null;

 logInfo("NEXT Run Date Set: [" + nextRunTime + "]");
 logInfo("LAST Run Date Retrieved (" + lastRunTime + ")");

 //Check for null so we can default the lastRunTime using the DEFAULT_LOOKBACK 
 if (lastRunTime == null || lastRunTime == "null" || lastRunTime == "") {

   logInfo("Empty Date Retrieved, setting to default lookback (-" + DEFAULT_LOOKBACK_DAYS + " days)");
   lastRunTime = new Date();
   lastRunTime.setDate(nextRunTime.getDate() - DEFAULT_LOOKBACK_DAYS);
   logInfo("LAST Run Date Set: [" + lastRunTime + "]");

 } 

 //Persist values through execution of this instance of the workflow.
 vars.lastRunTime = lastRunTime;
 vars.nextRunTime = nextRunTime;

 logInfo("Finished Execution.");
 logInfo("===================");
```

## Volgende video

[Een exportworkflow maken (deel 2) - Gegevens extraheren, opmaken en opslaan naar een externe account](extract-format-save-data-to-external-account.md)
