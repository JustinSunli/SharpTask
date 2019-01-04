---
layout: page
title: Modify Sheet Metal Thickness
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

This task helps users to change/modify the sheet metal thickness. Any values that is entered is considered to be in document units. 
 - Changes are done to the top level Sheet Metal feature in Feature Manger Design Tree.
 - Task works with Solidworks part file only
 - User can Enter value for New Thickness
 - User can Filter the bodies based on its thickness using Thickness filter
 - User can Increase or decrease the Present thickness based on Coefficient. All bodies that are filtered based on settings will be multiplied by the  coefficient value to calculate their new thickness


A comparative view of a drawing processed using Activate Sheet task is shown below.

![Comparision](002_ActivateSheet_002.png "Comparision between initial and final state of Solidworks Drawing")

## File Types

| Supported | Description |
| --- | --- |
| SLDPRT | Supports SolidWorks Part Files only |


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
