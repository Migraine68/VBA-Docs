---
title: Application.ActiveWorkbook property (Excel)
keywords: vbaxl10.chm183081
f1_keywords:
- vbaxl10.chm183081
ms.prod: excel
api_name:
- Excel.Application.ActiveWorkbook
ms.assetid: 637a2a30-f80c-08cd-e5c2-84716d0fff01
ms.date: 06/08/2017
localization_priority: Normal
---


# Application.ActiveWorkbook property (Excel)

Returns a  **[Workbook](Excel.Workbook.md)** object that represents the workbook in the active window (the window on top). Read-only. Returns **Nothing** if there are no windows open or if either the Info window or the Clipboard window is the active window.


 **Note**  The document in the active protected view window cannot be accessed using this property. Instead, use the  **[Workbook](Excel.ProtectedViewWindow.Workbook.md)** property of the **[ProtectedViewWindow](Excel.ProtectedViewWindow.md)** object.


## Syntax

_expression_. `ActiveWorkbook`

_expression_ A variable that represents an [Application](Excel.Application-graph-property.md) object.


## Example

This example displays the name of the active workbook.


```vb
MsgBox "The name of the active workbook is " & ActiveWorkbook.Name
```


## See also


[Application Object](Excel.Application(object).md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
