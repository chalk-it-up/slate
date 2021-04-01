## Update School Event
This endpoint can be used to update the details of a school event.

```shell
http PUT example.com/api/schools/143620604850191/events/96042210856992
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/schools/{schoolId}/events/{eventId}`

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

> The above command returns JSON structured like below.

{
    "success": true,
    "message": "Ok",
    "data": {       
        "event_id": 143624449953854,
        "name": "School Event Name Changed",
        "description": "Longer narrative about the event changed",
        "org_id": 143624423903247,
        "recurrence": "Weekly",
        "start_date": "2020-10-01",
        "end_date": "2020-10-30",
        "days_of_week": "NNNNNYN",
        "start_time": "12:00",
        "end_time": "15:00",
        "capacity": 20,
        "updated_by": 143624424788026
    }
}
