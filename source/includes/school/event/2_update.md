## Update School Event
This endpoint can be used to update the details of a school event.

```shell
http PUT example.com/api/events/143620604850191
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/events/{id}`

### Parameters

Parameter | Description
--------- | -----------
name | The name of the event
description | A longer description of the event
org_id | The organisation (school) that the event is linked to
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
      "event_id": 164125152636999,
      "name": "School Event Name Changed",
      "description": "Longer narrative about the event changed",
      "org_id": 164125131157521,
      "recurrence": "Weekly",
      "start_date": "2021-06-01",
      "end_date": "2021-06-30",
      "days_of_week": [
        "Saturday"
      ],
      "start_time": "12:00",
      "end_time": "15:00",
      "booking_closes": 60,
      "capacity": 20,
      "updated_by": 164125132058690,
      "tags": [
        "Community"
      ]
    }
}
```
