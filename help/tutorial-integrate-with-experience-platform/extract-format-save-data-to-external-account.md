---
title: Een exportworkflow maken (deel 2) - Gegevens extraheren, opmaken en opslaan naar een extern account
description: Leer in dit tweede deel van de tutorial Een exportworkflow maken hoe u de exportgegevens kunt opmaken en hoe u de gegevens naar een extern account kunt opslaan.
feature: Data Management, Workflows
jira: KT-8160
thumbnail: 336391.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: ac29b75c-a838-4183-8ec5-034281290725
source-git-commit: a6b4e7f12c6565bcef644705b23f96803c5b6f85
workflow-type: ht
source-wordcount: '92'
ht-degree: 100%

---

# Een exportworkflow maken (deel 2): Gegevens extraheren, opmaken en opslaan naar een extern account

Leer in dit tweede deel van de tutorial Een exportworkflow maken hoe u de exportgegevens kunt opmaken en hoe u de gegevens naar een extern account kunt opslaan.

>[!VIDEO](https://video.tv.adobe.com/v/336391?quality=12&learn=on)

## Assets

JavaScript: datum opslaan

```java
 logInfo("=====================")
 logInfo("Starting Execution...")

 optionName = vars.OPTION_NAME;
 logInfo("optionName: " + optionName);
 logInfo("NEXT Run Date: " + vars.nextRunTime);
 
 //Make sure we have valid values before saving for next run
 if (vars.nextRunTime == null || optionName == null){

   logInfo("Unable to find non-null values for optionName/nextRunTime! Throwing Error.")
   throw new Error('Unable to find non-null values for optionName/nextRunTime!  Ending Execution.');

 } else {

   // Save the nextRunTime to the database to establish starting point for next run.
   setOption(optionName, vars.nextRunTime);
   logInfo("Date Saved. [" + optionName + "] = [" + vars.lastRunTime + "]")

 }

 logInfo("Finished Execution.") 
 logInfo("===================")
```
