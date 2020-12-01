## Search Events
This endpoint allows for events to be listed across all charities.
 
```shell
http GET example.com/api/events?id_province=3&tag=5&offset=0&limit=10
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/events?id_province=3&tag=5&offset=0&limit=10`

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
            "start_date": "2020-12-21",
            "end_date": "2020-12-25",
            "days_of_week": "YNYNYNN",
            "start_time": "16:00",
            "end_time": "18:00",
            "capacity": 15
        }
    ]
}
```
