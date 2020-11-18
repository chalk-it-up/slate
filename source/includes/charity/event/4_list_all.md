## Search Events
This endpoint allows for events to be listed across all charities.
 
```shell
http GET example.com/api/TBD?id_province=3&tag=5&offset=0&limit=10
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/TBD?id_province=3&tag=5&offset=0&limit=10`

### Parameters

Parameter | Description
--------- | -----------
id_province | The province to filter by
tag | The tag/category to filter by
offset | The starting record (for pagination)
limit | The number of records to return

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": [
        {
            "event_id": 96042210856992,
            "event_name": "Test Event #2",
            "charity_id": 96042186387470,
            "charity_name": "Ekklesia Park",
            "recurrence": "Once Off2",
            "start_time": "2020-12-25T16:00:00Z",
            "end_time": "2020-12-25T18:00:00Z",
            "capacity": 15
        }
    ]
}
```
