---
layout: page
title: Bulk Property Import
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

This task can be used to import metadata present in an excel file against Custom and Configuration specific properties.
 - Import Properties from excel into Solidworks files referenced by its path and configuration name
 - User can choose the file name from which the properties are to be imported.
 - User can specify the file path where the file is located. 
 - Options to choose to Import Generic or Configuration Specific properties or Empty Properties
 If user does not choose to import empty properties, then properties without values against the specific Solidworks file will not be imported
This task works best with 'Bulk Property Export' task.

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
  <source src="http://cloud.ic3d.com.au.s3.amazonaws.com/sharp_task/library/mdl_export_import_custom_prop/res/BULK_PROPERTY.mp4" type="video/mp4">
</video>



## Download Sample Files

Sample files can be downloaded from 
[Sample Model in Solidworks 2017](../000-model/SolidWorks_2017_RoboticArm.zip)

[Click to view the model at GrabCad](https://grabcad.com/library/5-dof-robot-1)
