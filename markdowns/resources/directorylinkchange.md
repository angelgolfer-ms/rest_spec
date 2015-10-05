# DirectoryLinkChange resource type



#### Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|associationType|String||
|deletionTimestamp|DateTimeOffset||
|objectId|String| Read-only.|
|objectType|String||
|sourceObjectId|String||
|sourceObjectType|String||
|sourceObjectUri|String||
|targetObjectId|String||
|targetObjectType|String||
|targetObjectUri|String||

#### Relationships
None


#### Tasks

| Task		   | Return Type	|Description|
|:---------------|:--------|:----------|
|[Get metadata](../api/directorylinkchange_get.md) | DirectoryLinkChange |Read properties and relationships of directoryLinkChange object.|
|[Update](../api/directorylinkchange_update.md) | DirectoryLinkChange	|Update directoryLinkChange object. |
|[Delete](../api/directorylinkchange_delete.md) | DirectoryLinkChange	|Update directoryLinkChange object. |
|[Checkmembergroups](../api/directorylinkchange_checkmembergroups.md)|String||
|[Get getMemberGroups](../api/directorylinkchange_getmembergroups.md)|String||
|[Get getMemberObjects](../api/directorylinkchange_getmemberobjects.md)|String||