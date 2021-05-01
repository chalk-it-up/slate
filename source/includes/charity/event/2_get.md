## Get Event Details
This endpoint returns the details for a single charity event.
 
```shell
http GET example.com/api/events/96042210856992
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/events/{eventId}`

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": {
        "event_id": 96042210856992,
        "event_name": "Test Event",
        "charity_id": 96042186387470,
        "charity_name": "Ekklesia Park",
        "recurrence": "Once Off",
        "start_date": "2020-12-21",
        "end_date": "2020-12-25",
        "days_of_week": [
          "mon",
          "wed",
          "fri"
        ],
        "start_time": "16:00",
        "end_time": "18:00",
        "capacity": 10
    }
}
```
