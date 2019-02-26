---
title: "auditResource resource type"
description: "A class containing the properties for Audit Resource."
author: "tfitzmac"
localization_priority: Normal
ms.prod: "Intune"
---

# auditResource resource type

> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

A class containing the properties for Audit Resource.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Display name.|
|modifiedProperties|[auditProperty](../resources/intune-auditing-auditproperty.md) collection|List of modified properties.|
|type|String|Audit resource's type.|
|resourceId|String|Audit resource's Id.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.auditResource"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.auditResource",
  "displayName": "String",
  "modifiedProperties": [
    {
      "@odata.type": "microsoft.graph.auditProperty",
      "displayName": "String",
      "oldValue": "String",
      "newValue": "String"
    }
  ],
  "type": "String",
  "resourceId": "String"
}
```



