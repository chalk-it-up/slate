# School Events

## Add School Event
This endpoint can be used to add an event for a school.


```shell
http POST example.com/api/schools/143620604850191/events
```

```javascript
TODO
```

### HTTP Request

`POST example.com/api/schools/{schoolId}/events`

### Parameters

Parameter | Description
--------- | -----------
name | The name of the event
description | A longer description of the event
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
        "name": "School Event Name",
        "description": "Longer narrative about the event",
        "org_id": 143622650753039,
        "recurrence": "Weekly",
        "start_date": "2020-10-01",
        "end_date": "2020-10-30",
        "days_of_week": "NNNNNYN",
        "start_time": "12:00",
        "end_time": "14:00",
        "capacity": 10,
        "updated_by": 143622651637818,
        "event_id": 143622675918910
    }
}
```
