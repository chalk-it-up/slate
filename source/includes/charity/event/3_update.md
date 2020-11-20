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
