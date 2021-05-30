# Events

## Add Event
This endpoint can be used to add an event for an organisation (school or charity).

```shell
http POST example.com/api/events
```

```javascript
TODO
```

### HTTP Request

`POST example.com/api/events`

### Parameters

Parameter | Description
--------- | -----------
name | The name of the event
description | A longer description of the event
org_id | The organisation that the event is linked to
recurrence | How often the event is hosted
start_date | The starting date from when the series is valid
end_date | The end date after which the event is no longer valid
days_of_week | The days of the week that the event is available
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
      "name": "Test Event",
      "description": "Longer text about event",
      "org_id": 164118011572252,
      "recurrence": "Weekly",
      "start_date": "2021-05-29",
      "end_date": "2021-06-05",
      "days_of_week": [
        "Monday",
        "Tuesday",
        "Wednesday",
        "Thursday",
        "Friday",
        "Saturday",
        "Sunday"
      ],
      "start_time": "16:00",
      "end_time": "17:00",
      "booking_closes": 60,
      "capacity": 10,
      "updated_by": 164118012424256,
      "tags": [
        "Sport"
      ],
      "event_id": 164118033510471
    }
}
```
