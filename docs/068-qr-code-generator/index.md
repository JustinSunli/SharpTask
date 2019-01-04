---
layout: page
title: QR Code Generator
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

This task helps user generate a QR Code [Quick Response Code] and insert it into drawing sheet format.  Task works with Solidworks Drawings only.
 - QR Code Value: User can choose to enter a Text to Place into Sheet
 - QR Code Location: User can choose a predefined reference location to place the QR Code:  Top Left, Top Right, Bottom Left, Bottom Right
 - User can also specify the Offset from reference location. The units are taken from document properties. X and Y Offset
 - Offsets can be specified in terms of X and Y Distances
      For Top Left > X is Positive and Y is Negative
      For Bottom Left > Both X and Y are positive
      For Top Right > Both X and Y are negative
      For Bottom Right > X is negative and Y is Positive
 - Width and Height of the QR Code to be placed on the drawing sheet.
 - Task works with Solidworks Drawings only.
 - Enable ""Run Macro on each configuration"" to place on each sheet.


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
