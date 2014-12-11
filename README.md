# MS CRM 4.0 Sensor Pack

## Overview

This Knowledge Sensor Pack can be used to help quantify and diagnose performance issues related to Microsoft CRM 
version 4.0 specific code

| Name | Microsoft CRM V4.0 Sensor Pack
| :--- | :---
| Author | dynaTrace software
| Supported dynaTrace Version | >= 5.5
| License | [dynaTrace BSD](dynaTraceBSD.txt)
| Support | [Community](https://community.compuwareapm.com/community/display/DL/Support+Levels#SupportLevels-Community)
| Release history | Version 1.0
| Download | [dynaTrace_MS_CRM_v4.0_for_dt30.zip](dynaTrace_MS_CRM_v4.0_for_dt30.zip)

## Sensor Pack Description

This Sensor Pack has not been tested under heavy production load. This Sensor Pack was designed with production in mind but please test with your specific application before putting this Sensor Pack
into a production environment.

## Installation

  1. Save the attached file locally to the computer where the dynaTrace Diagnostics Client is installed. 

  2. Unzip the file. 

  3. In the dynaTrace Diagnostics Client, right-click on the Diagnostics Server and select 'Preferences...'. 

  4. Click on "Sensor Packs". 

  5. Click on the "Import..." button. 

  6. Select "Custom Sensor Type (*.dtdcs)" in the "Files of type" dropdown. 

  7. Navigate to the directory where you extracted the .dtdcs file and click "Open". 

You can confirm successful import by observing the MS CRM 4 Sensor Pack in the Sensor Packs Panel. This Knowlege Sensor Pack is now _Placed_ and _Active_ within all System Profiles on this Diagnostics
Server.

Exercise the MS CRM 4 application and open up the API view to see the new "MS CRM 4" API

