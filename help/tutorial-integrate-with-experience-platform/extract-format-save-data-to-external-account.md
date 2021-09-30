---
title: Een exportworkflow maken (deel 2) - Gegevens extraheren, opmaken en opslaan naar een externe account
Description: In this second part of the Create an Export Workflow tutorial, you learn how to format the data for export and how to save the data to an external account. 
feature: Data Import/Export, Workflows
kt: 8160
thumbnail: 336391.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
source-git-commit: 9a75069ee3bb9352ba7fa5350eb54e421e9427c8
workflow-type: tm+mt
source-wordcount: '62'
ht-degree: 0%

---


# Een exportworkflow maken (deel 2): Gegevens extraheren, opmaken en opslaan naar een externe account

In dit tweede deel van de zelfstudie Een exportworkflow maken leert u hoe u de gegevens kunt opmaken voor export en hoe u de gegevens kunt opslaan in een externe account.

>[!VIDEO](https://video.tv.adobe.com/v/336391?quality=12)

## Activa

JavaScript: Datum opslaan

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


