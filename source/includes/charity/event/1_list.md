## Get All Events for a Charity
This endpoint returns a list of events associated with a charity.
 
```shell
http GET example.com/api/charities/96042186387470/events
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/charities/{charityId}/events`

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


