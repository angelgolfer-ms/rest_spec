# List DirectoryObject

Retrieve a list of directoryobject objects.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
GET /directoryObjects
```
### Optional query parameters
|Name|Value|Description|
|:---------------|:--------|:-------|
|$orderby|string|Comma-separated list of properties that are used to sort the order of items in the response collection.|

### Request headers
| Name       | Type | Description|
|:-----------|:------|:----------|
| X-Sample-Header  | string  | Sample HTTP header. Update accordingly or remove if not needed|

### Request body
Do not supply a request body for this method.
### Response
If successful, this method returns a `200 OK` response code and collection of [DirectoryObject](../resources/directoryobject.md) objects in the response body.
### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "get_directoryobjects"
}-->
```http
GET /directoryObjects
```
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "microsoft.graph.directoryobject",
  "isCollection": true
} -->
```http
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 152

{
  "value": [
    {
      "objectType": "objectType-value",
      "objectId": "objectId-value",
      "deletionTimestamp": "datetime-value"
    }
  ]
}
```

<!-- uuid: 1ec6c637-d5ce-4c7c-8510-60a02b97903c
2015-10-25 13:14:09 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "List DirectoryObject",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->