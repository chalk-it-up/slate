# Charity Events

## Add Charity Event
This endpoint can be used to add an event for a charity.


```shell
http POST example.com/api/charities/2327833979673121796/events
```

```javascript
TODO
```

### HTTP Request

`POST example.com/api/charities/{charityId}/events`

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

> The above command returns JSON structured like below where id is the identity of the event added.

```json
{
    "success": true,
    "data": {
        "event_id": 96042210856992
    }
}
```
