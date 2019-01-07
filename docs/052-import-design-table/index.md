---
layout: page
title: Import Design Table
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

The task is used to import design table into Solidworks Part or Assembly. 
 - The file(s) against which it is executed should have a Design Table Feature existing in the Configurations Tab 
 - The task works best with `Export Design Table`
 - Excel can show additional popup messages which require user input during process. Pop up could be disabled using the method from this article   [Link to Microsoft]("https://support.microsoft.com/en-au/kb/948615" )
 - Task can works with Solidworks Part and Assembly files

A comparative view of a drawing processed using Activate Sheet task is shown below.

![Comparision](002_ActivateSheet_002.png "Comparision between initial and final state of Solidworks Drawing")

## File Types

| Supported | Description |
| --- | --- |
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
