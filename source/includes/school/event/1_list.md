## Get All Events for a School
This endpoint returns a list of events associated with a school.
 
```shell
http GET example.com/api/schools/143624423903247/events
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/schools/{schoolId}/events`

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": [
        {
            "event_id": 143624449953854,
            "name": "School Event Name Changed",
            "description": "Longer narrative about the event changed",
            "org_id": 143624423903247,
            "org_name": "St Stithians Boys' College",
            "org_type": "S",
            "recurrence": "Weekly",
            "start_date": "2020-10-01",
            "days_of_week": "NNNNNYN",
            "end_date": "2020-10-30",
            "start_time": "12:00",
            "end_time": "15:00",
            "capacity": 20,
            "street": "40 Peter Place",
            "suburb": "Lyme Park",
            "city": "Sandton",
            "province_id": 3,
            "email": "info@stithian.com",
            "telephone": "011 577 6000",
            "website": "https://www.stithian.com/",
            "gps_coords": "W299+47 Sandton",
            "enabled": true,
            "time_created": "2021-04-01T16:29:36.787686Z",
            "images": []
        }
    ]
}
```


