---
layout: page
title: Update and Save
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

The task can be used to save an existing Solidworks file from a current version to a future version if there are multiple versions of Solidworks installed. The macro automatically saves the original model.
 - It is recommended to use this macro after creating a backup copy of input files. Files can be backed up using Backup Options > Always Enabled
 - User should enable the option ""Allow to resaving to newer versions""
 - User can Resize the model to Zoom - Fit the window and saves.
 - User can also choose to "Rebuild" files and save.


A comparative view of a drawing processed using Activate Sheet task is shown below.

![Comparision](002_ActivateSheet_002.png "Comparision between initial and final state of Solidworks Drawing")

## File Types

| Supported | Description |
| --- | --- |
| SLDDRW | Supports SolidWorks Drawing Files |
| SLDPRT | Supports SolidWorks Part Files |
| SLDASM | Supports SolidWorks Assembly Files |


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