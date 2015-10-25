# Create File

Use this API to create a new File.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
POST /users/<objectId>/TrendingAround
POST /drive/root/createdByUser/TrendingAround
POST /drive/root/lastModifiedByUser/TrendingAround

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample HTTP header. Update accordingly or remove if not needed|

### Request body
In the request body, supply a JSON representation of [File](../resources/file.md) object.


### Response
If successful, this method returns `201, Created` response code and [File](../resources/file.md) object in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "create_file_from_messages"
}-->
```http
POST /users/<objectId>
```
In the request body, supply a JSON representation of [File](../resources/file.md) object.
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "microsoft.graph.file"
} -->
```http
HTTP/1.1 201 Created
Content-type: application/json
Content-length: 3

{
}
```

<!-- uuid: 1ec6c637-d5ce-4c7c-8510-60a02b97903c
2015-10-25 13:14:09 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Create File",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->