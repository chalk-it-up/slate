## Get Event Details
This endpoint returns the details for a single school event.
 
```shell
http GET example.com/api/events/143624449953854
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/events/{id}`

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": {
      "event_id": 164125152636999,
      "name": "School Event Name Changed",
      "description": "Longer narrative about the event changed",
      "org_id": 164125131157521,
      "org_name": "St Stithians Boys' College",
      "org_type": "S",
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
      "slots_booked": 0,
      "slots_available": 20,
      "street": "40 Peter Place",
      "suburb": "Lyme Park",
      "city": "Sandton",
      "province_id": 3,
      "province": "Gauteng",
      "email": "info@stithian.com",
      "telephone": "011 577 6000",
      "website": "https://www.stithian.com/",
      "gps_coords": "W299+47 Sandton",
      "tags": [
        "Community"
      ],
      "images": []
    }
}
```
