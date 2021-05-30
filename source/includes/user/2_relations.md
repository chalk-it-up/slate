## User Relations
This endpoint returns the relationships of the parent user.
 
```shell
http GET example.com/api/users/{id}/relations
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/users/{id}/relations`

> The above command returns JSON structured like this:

```json
{
  "success": true,
  "message": "ok",
  "data": [
    {
        "id": 1124662724344876291,
        "first_name": "Joey",
        "last_name": "Soap",
        "relationship": "child"
    },
    {
        "id": 1124662724344876291,
        "first_name": "Amy",
        "last_name": "Waters",
        "relationship": "child"
    }
  ]
}
```


