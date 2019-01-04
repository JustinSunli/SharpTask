---
layout: page
title: Shop Drawings
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

The task can be used to generate shop drawings from Solidworks models. It can automatically generate drawing views for each body in a multibody part.
 - User can provide an Output file name: Can be composed of Current Date, Custom Property Value, Solidworks Title or Configuration Name
 - Select a Destination Folder by Path or using the folder browse control
 - Choose full Path to the Template [including extension .drwdot]
 - User can also choose to ""Place All views on Single Sheet""
 - User can choose to "```Process Each Body```"
 - Select a Paper size from a list of Standard Sizes


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
