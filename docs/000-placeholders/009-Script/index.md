---
layout: page
title: Scripts
author: Artem Taturevych
---

## Introduction

Script placeholder allows to return the value based on the custom code in C# or VB.NET language based on .NET Framework 4.0.

To create a code it is required to implement the body of function which returns the string value (to be used as a placeholder replacement result).

Pointer to the SOLIDWORKS application ([ISldWorks interface](http://help.solidworks.com/2012/english/api/sldworksapi/solidworks.interop.sldworks~solidworks.interop.sldworks.isldworks.html)) is provided via *Application* property. It is required to use late binding to access the properties and methods.

For C# script several helper functions are available to invoke the late binding members of the SOLIDWORKS interfaces:

* Get(pointer to dispatch, property name) - returns the value of the property as object
* Get<Type>(pointer to dispatch, property name) - returns the value of the property as specified Type
* Set(pointer to dispatch, property name, property value) - sets the value of the property
* Call(pointer to dispatch, method name, method parameters) - invokes the 
method and returns the value as object (null if void)
* Call<Type>(pointer to dispatch, method name, method parameters) - invokes the method and returns the value as Type (null if void)

## Examples

### Get Name Of First Body (C#)

Returns the name of the first solid body in the part document.

~~~ cs
var part = Call(Application, "ActiveDoc");

const int swSolidBody = 0;

var bodies = Call<object[]>(part, "GetBodies2", swSolidBody, true);

if (bodies != null && bodies.Length > 0)
{
    return Get<string>(bodies[0], "Name");
}
else
{
    return "";
}
~~~

### Increment Counter (C#)

Generates next sequential number. Number is stored in the *C:\counter.ini* file.

~~~ cs
const string COUNTER_FILE_PATH = @"C:\counter.ini";

int nextNumber;

if (System.IO.File.Exists(COUNTER_FILE_PATH))
{
    int.TryParse(System.IO.File.ReadAllText(COUNTER_FILE_PATH), out nextNumber);
    nextNumber++;
}
else
{
    nextNumber = 1;
}

System.IO.File.WriteAllText(COUNTER_FILE_PATH, nextNumber.ToString());

return nextNumber.ToString();
~~~

### Get Cut List Property (VB.NET)

Returns the value of DESCRIPTION custom property from the first cut-list item in the weldment part.

~~~ vb
Const PRP_NAME As String = "DESCRIPTION"

Dim part As Object = Application.ActiveDoc

If part.IsWeldment() Then

    Dim feat As Object
    feat = part.FirstFeature()

    While feat IsNot Nothing And feat.GetTypeName() <> "CutListFolder"
        feat = feat.GetNextFeature()
    End While

    If feat IsNot Nothing Then
        Dim cutListFolder As Object
        cutListFolder = feat.GetSpecificFeature()
        cutListFolder.UpdateCutList()

        Dim custPrpMgr As Object
        custPrpMgr = feat.CustomPropertyManager
        Dim prpVal As String = custPrpMgr.Get(PRP_NAME)

        Return prpVal

    End If

End If

Return ""
~~~