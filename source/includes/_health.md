## Health
This endpoint returns the health of the system.

This endpoint is unique in that two methods are supported HEAD (preferred) and GET.

No authentication header is required for this endpoint.

```shell
http HEAD <%= config[:endpoint] %>/health "Authorization:Bearer $AUTH_TOKEN"
```

```javascript
TODO
```

### HTTP Request

`HEAD <%= config[:endpoint] %>/health`

Returns HTTP status code 200 and no content

`GET <%= config[:endpoint] %>/health`

Returns HTTP status code 200 and content `OK`
