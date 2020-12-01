## List Event Instances
This endpoint allows for event instances to be listed.
 
```shell
http GET example.com/api/events/816546547/instances?offset=0&limit=10
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/events/{id}/instances?offset=0&limit=10`

### Parameters

Parameter | Description
--------- | -----------
offset | The starting record (for pagination)
limit | The number of records to return

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": [
        { "event_date": "2020-12-21" },
        { "event_date": "2020-12-23" },
        { "event_date": "2020-12-25" }
    ]
}
```
