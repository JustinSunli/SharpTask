---
layout: page
title: Expport Tables
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

The task can be used to export the tables that are applied within Solidworks Part, Assembly and Drawing files
 - User can specify the Output Folder Name or use the browse control to choose a target folder
 - User can choose the Table types to export: BOM, Weldment Cutlist, General, Revision and Hole Table
 - Format for Output can be Set to CSV or TXT
 - Output File name can be configured using Placeholders. By default it is set to [title]_[tableName]. 
 - User can specify text/phrase to Match.


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
