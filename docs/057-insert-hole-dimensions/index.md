---
layout: page
title: Insert Hole Dimensions
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

This task is helpful in inserting hole diameter and the position of hole from an edge. 
 - Considers drawing views which contains reference to parts only 
 - Assemblies are not dimensioned.   
 - Holes with the  same diameters are grouped together. 
 - Threads are dimensioned by referencing to its inner diameter. 
 - Edge Chamfers are dimensioned as inner and outer diameters. 
 - Holes that are linear patterned are dimensioned by their centres. 
 - The units and accuracy (decimal places) is controlled by the document properties.
 - Task works with Solidworks Drawings only [*.SLDDRW].

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
