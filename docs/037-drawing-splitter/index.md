---
layout: page
title: Drawing Splitter
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

This task processes each drawing sheet and saves it as a new Solidworks Drawing file. 
 - The input drawing file is not modified.
 - Recommended to use ""Open Read Only"" setting in #Task
 - Use ""Run macro on each configuration"" to save each sheet present in a multi sheet drawing as a separate Solidworks drawing file
 - By default, Output Drawing name is set as [title]_[configuration] and saved as slddrw format. It may contain text or placeholders
 - User can directly enter the path to destination folder or use the browse control to choose one


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
