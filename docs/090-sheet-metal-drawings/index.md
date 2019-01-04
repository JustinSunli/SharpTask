---
layout: page
title: Sheet Metal Drawings
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

This task provides the feasibility to create Solidworks drawings for Sheet Metal components.  A single Solidworks drawing file is generated from all solidworks part files present in items scope.
 - Option to specify a name for the Output File.
    User can type in the name for the new file or choose from a list of Placeholders like Current Date, Custom Property Value, Solidworks Title, Solidworks Configuration or Sheet Name
 - Choose a Destination Folder where the Output files have to be stored
 - Choose a path to the Template file.


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
