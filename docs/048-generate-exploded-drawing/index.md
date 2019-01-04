---
layout: page
title: Generate Exploded Drawing
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

The task assists in automatically generating a new drawing file containing exploded view.
 - Output File Name: user can provide a preffered file name for the drawing to be saved as. It can also be composed using placeholders like Current Date, Custom Property,     Regular Expression, Scripts, Solidworks Configuration / Sheet Name, Solidworks Title, Solidworks Part Number, Model Location path
 - Destination Folder: User can specify the target folder using a path or browse folder control
 - Template Path; User can specify a path to the Template or select using the browse file control [.drwdot]
 - Paper Size: user can choose a paper size for the drawing
 - Orientation: User can Choose from one of the available views
 - Scale: Sacle will be applied to all drawing views on drawing sheet. Value can be entered as a ratio or decimal number


A comparative view of a drawing processed using Activate Sheet task is shown below.

![Comparision](002_ActivateSheet_002.png "Comparision between initial and final state of Solidworks Drawing")

## File Types

| Supported | Description |
| --- | --- |
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
