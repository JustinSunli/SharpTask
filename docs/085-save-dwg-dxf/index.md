---
layout: page
title: Save DWG / DXF
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

The task helps in saving Solidworks Drawing files to DWG/DXF format. This is performed using the default export options in Solidworks settings. User can set these options each time while saving the file to DWG / DXF format. The task provides user with options during export.
 - Output File Name: User can choose to select placeholders to construct the file naming or directly insert the output file name into the field.
 - Extension: User can choose to output the file in DWG or DXF format
 - Destination Folder: User can enter the path as text or use the browse folder control to choose the target folder
 - Multiple Sheet Options: Options to Export specified sheets, Export all sheets to  separate files or Export all sheets to one file
 - Export Specified Sheets: User can specify sheet names to export or use asterisk symbol to process all sheets.


A comparative view of a drawing processed using Activate Sheet task is shown below.

![Comparision](002_ActivateSheet_002.png "Comparision between initial and final state of Solidworks Drawing")

## File Types

| Supported | Description |
| --- | --- |
| SLDDRW | Supports SolidWorks Drawing Files only |


## Download & Task Setup

User can download this task from online library performing search using keywords.
Select the task in Tasks list and setup arguments as required.

| Argument | Details |
| --- | --- |
| Sheet Name / Number| Enter name of Sheet which needs to be activated. Alternatively, a sheet number can be specified |
| Options | User can select one or more options from pick list |
| Zoom to Fit | Sets the model to fit within SolidWorks layout. Similar to using ```Shortcut Key "F"``` within SolidWorks |


Click on "Run Job" to initiate.

Once Job is completed, the target sheet is activated.

Below is a video of demonstrating activate sheet task in usage

<video width="720" height="480" controls>
  <source src="002_ActivateSheet.swf" type="video/mp4">
</video>


## Download Sample Files

Sample files can be downloaded from 
[Sample Model in Solidworks 2017](../000-model/SolidWorks_2017_RoboticArm.zip)

[Click to view the model at GrabCad](https://grabcad.com/library/5-dof-robot-1)
