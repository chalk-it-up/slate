## Update Charity Event
This endpoint can be used to update the details of a charity event.

```shell
http PUT example.com/api/events/96042210856992
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/events/{eventId}`

### Parameters

Parameter | Description
--------- | -----------
event_name | The name of the event
recurrence | How often the event is hosted
start_date | The starting date from when the series is valid
end_date | The end date after which the event is no longer valid
days_of_week | The days of the week that the event is available
start_time | The time that the event starts at
end_time | The time that the event ends
capacity | The number of attendees possible

> The above command returns JSON structured like below.

{
    "success": true,
    "message": "Ok",
    "data": {       
    }
}
