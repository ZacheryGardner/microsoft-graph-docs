---
title: "managementConditionExpressionString resource type"
description: "A management condition expression string is a string representation of a management condition expression."
author: "jaiprakashmb"
localization_priority: Normal
ms.prod: "intune"
doc_type: resourcePageType
---

# managementConditionExpressionString resource type

Namespace: microsoft.graph

> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

A management condition expression string is a string representation of a management condition expression.


Inherits from [managementConditionExpression](../resources/intune-fencing-managementconditionexpression.md)

## Properties
|Property|Type|Description|
|:---|:---|:---|
|value|String|The management condition statement expression string value.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.managementConditionExpressionString"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.managementConditionExpressionString",
  "value": "String"
}
```
