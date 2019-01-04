---
layout: page
title: Export BOM
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

The task can be used to export Bill of Materials from Solidworks Drawing or Assembly files.
 - To export data, BOM table should exist
 - Allows user to Add Columns and Fill data using Placeholders
    Image: Captures Image of the Part within BOM Table. User can specify the Height and Width of the image. User can choose to capture Photo Realistic Images using PhotoView 360. View orientation can be set before capturing the image.
    Hyperlink: Hyperlink can be inserted to link each Item in the BOM table to its Part. User can choose to display specific text instead of  path to file


A comparative view of a drawing processed using Activate Sheet task is shown below.

![Comparision](002_ActivateSheet_002.png "Comparision between initial and final state of Solidworks Drawing")

## File Types

| Supported | Description |
| --- | --- |
| SLDDRW | Supports SolidWorks Drawing Files |
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
