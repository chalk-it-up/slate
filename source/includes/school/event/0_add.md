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

`POST example.com/api/events/{id}`

### Parameters

Parameter | Description
--------- | -----------
name | The name of the event
description | A longer description of the event
org_id | The organisation (school) that the event is linked to
recurrence | How often the event is hosted
start_date | The starting date from when the series is valid
end_date | The end date after which the event is no longer valid
days_of_week | The days of the week that the event is available. A list where values are ("mon", "tue", "wed", "thu", "fri", "sat", "sun")
start_time | The time that the event starts at
end_time | The time that the event ends
capacity | The number of attendees possible
booking_closes | The time in minutes before the event that booking closes
tags | A list of tags associated with the event

> The above command returns JSON structured like below where id is the identity of the event added.

```json
{
    "success": true,
    "data": {
        "name": "School Event Name",
        "description": "Longer narrative about the event",
        "org_id": 164125131157521,
        "recurrence": "Weekly",
        "start_date": "2020-10-01",
        "end_date": "2020-10-30",
        "days_of_week": [
          "Saturday"
        ],
        "start_time": "12:00",
        "end_time": "14:00",
        "capacity": 10,
        "booking_closes": 60,
        "updated_by": 143622651637818,
        "tags": [
          "Community"
        ],
        "event_id": 143622675918910
    }
}
```
