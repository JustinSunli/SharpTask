---
layout: page
title: Display Sheet Format
---

## Task Description

![Activate Sheet](002_ActivateSheet_001.png "Activate Sheet")

This task allows to hide/show sheet template on active drawing sheet. The visibility could be changed for all sheets on drawing by selecting an option in #TASK to run for each sheet. Optionally could be nominated specific sheets (by name, by number or by template) for which this task should work. If conditions were specified in several tables ("Which Sheets" and "Which Formats") then the task will work only if conditions from both tables were met.


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
