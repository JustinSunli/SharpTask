---
layout: page
title: [#TASK Placeholders]
author: Vineet Reddy
---

## Introduction

Within the scope of ```#TASK```, Placeholders play a vital role. These are the dynamics variables that are populated during a job run. With the availibility of placeholders during the job run, a lot of scenarios are catered.

For example, 

```gherkin
Scenario: Save Solidworks Drawing as PDF while fetching filename from Part Number custom property
    Given Solidworks Drawing Files are added into Items Scope
    And Save to PDF Task is added to Tasks list
    And Filename is set to use "Part Number" custom property
    When User clicks on "Run Job"
    Then PDF files are produced in Output folder with Filename as Part Number featched from each Solidworks Drawing File

```

## List of Placeholders

![List of available Placeholders in #TASK](000_ListofPlaceholders.png "Placeholders in #TASK")

Following are the list of Placeholders available through #TASK Application as a platform feature.

### 1. Current Date
![CurrentDate](000_Placeholder_CurentDate.png "Placeholders for Current Date")


### 2. Script
![Script](000_Placeholder_Script.png "Placeholders for Script")


### 3. Regular Expression
![RegExp](000_Placeholder_RegExp.png "Placeholders for Regular Expression")


### 4. Vertical Table lookup
![LookUp](000_Placeholder_Lookup.png "Placeholders for Vertical Table Lookup")


### 5. Datasource
![SQL DataSource](000_Placeholder_DataSource_SQL.png "Placeholders for SQL DataSource")

![ODBC DataSource](000_Placeholder_DataSource_ODBC.png "Placeholders for ODBC DataSource")

![OLEDB DataSource](000_Placeholder_DataSource_OleDB.png "Placeholders for OleDB DataSource")

### 6. Custom Property value
![CustProp](000_Placeholder_CustProp.png "Placeholders for Custom Property")


### 7. Solidworks Model Title
![SWTitle](000_Placeholder_SWModelTitle.png "Placeholders for Solidworks Title")


### 8. Solidworks Active Model Configuration or Sheet Name
![SWConfSheet](000_Placeholder_SWConfSheet.png "Placeholders for Solidworks Configuration / Sheet Name")


### 9. Solidworks Model Part Number
![SW PartNumber](000_Placeholder_SWPartNo.png "Placeholders for Soliworks Part Number")


### 10. Solidworks File Location
![SWFileLocation](000_Placeholder_SWModelLocation.png "Placeholders for File Location")


### 11. Compare
![Compare](000_Placeholder_Compare.png "Placeholders for Compare Function")

