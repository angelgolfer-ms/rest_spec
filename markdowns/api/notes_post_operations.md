# Create notesOperation

Use this API to create a new notesOperation.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http


```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample HTTP header. Update accordingly or remove if not needed|

### Request body
In the request body, supply a JSON representation of [notesOperation](../resources/notesoperation.md) object.


### Response
If successful, this method returns `201, Created` response code and [notesOperation](../resources/notesoperation.md) object in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "create_notesoperation_from_notes"
}-->
```http

```
In the request body, supply a JSON representation of [notesOperation](../resources/notesoperation.md) object.
##### Response
Here is an example of the response. Note: The response object may be truncated for brevity. All of the properties will be returned from an actual call.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.notesoperation"
} -->
```http
HTTP/1.1 201 Created
Content-type: application/json
Content-length: 3

{
}
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Create notesOperation",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->