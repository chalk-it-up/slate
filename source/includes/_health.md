## Health
This endpoint returns the health of the system.

This endpoint is unique in that two methods are supported HEAD (preferred) and GET.

No authentication header is required for this endpoint.

```shell
http HEAD example.com/health
```

```javascript
TODO
```

### HTTP Request

`HEAD example.com/health`

Returns HTTP status code 200 and no content

`GET example.com/health`

Returns HTTP status code 200 and content `OK`
