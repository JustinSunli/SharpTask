---
layout: page
title: Generate Report of Volumes
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

This task allows to generate a detailed report of volumes of Part or Assembly and units is set to mm<sup>3</sup>.
 - Traverses through an Assembly and lists all the configurations
 - Traverses through each body and provides the values against each of them
 - The output for a particular run is cumulated into a single excel file
 - If output folder is not specified, then Report is saved to parent folder for each file
 - If Output folder is specified, then a single Report file is saved
 - For readability, #TASK inserts a blank row after each file is processed
 - This task processes only Solidworks Part and Assembly files. [*SLDPRT, *.SLDASM]


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
