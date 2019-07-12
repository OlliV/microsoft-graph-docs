---
title: "userTeamwork resource type"
description: "A container for Microsoft Teams features available per user. "
author: "anandjo"
localization_priority: Priority
ms.prod: "microsoft-teams"
---

# userTeamwork resource type

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

UserTeamwork is a container for the range of Microsoft Teams functionalities that are available per user in the tenant.

## Methods

| Method       | Return Type  |Description|
|:---------------|:--------|:----------|

## Properties

| Property | Type	| Description |
|:---------------|:--------|:----------|
|id|string| A unique identifier. |

## Relationships

| Relationship | Type	| Description |
|:---------------|:--------|:----------|
|installedApps|[teamsAppInstallation](teamsappinstallation.md) collection|The apps installed in the personal scope of this user.|

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.userTeamwork",
  "baseType": "microsoft.graph.entity"
}-->

```json
{
  "id": "string"
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "userteamwork resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": []
}
-->

## See Also

- [List apps installed for a user](../api/user-list-teamsappinstallation.md)
- [Install app for user](../api/user-add-teamsappinstallation.md)
- [Uninstall app for a user](../api/user-delete-teamsappinstallation.md)
- [Upgrade installed app for a user](../api/user-upgrade-teamsappinstallation.md)