## Update Event Details
This endpoint can be used to update the details of an event.

```shell
http PUT example.com/api/events/96042210856992
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/events/{id}`

### Parameters

Parameter | Description
--------- | -----------
org_id | The organisation that the event is linked to
event_name | The name of the event
description | A longer description of the event
recurrence | How often the event is hosted
start_date | The starting date from when the series is valid
end_date | The end date after which the event is no longer valid
days_of_week | The days of the week that the event is available
start_time | The time that the event starts at
end_time | The time that the event ends
capacity | The number of attendees possible
booking_closes | The time in minutes before the event that booking closes
tags | A list of tags associated with the event

> The above command returns JSON structured like below.

```json
{
    "success": true,
    "message": "Ok",
    "data": {       
      "event_id": 164118033510471,
      "name": "Test Event #2",
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
      "capacity": 15,
      "updated_by": 164118012424256,
      "tags": [
        "Sport"
      ]
  }
}
```
