## Health
This endpoint returns the health of the system.

This endpoint is unique in that two methods are supported HEAD (preferred) and GET.

No authentication header is required for this endpoint.

```shell
http HEAD chalky.com/health
```

```javascript
TODO
```

### HTTP Request

`HEAD chalky.com/health`

Returns HTTP status code 200 and no content

`GET chalky.com/health`

Returns HTTP status code 200 and content `OK`
