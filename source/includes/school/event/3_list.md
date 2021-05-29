## Get All Events for a School

This endpoint returns a list of events associated with a school.

```shell
http GET example.com/api/events?org_id=143624423903247
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/events?org_id={id}`

> The above command returns JSON structured like this:

```json
{
  "success": true,
  "message": "Ok",
  "data": [
    {
      "event_id": 164125131657265,
      "name": "School Cleanup",
      "description": "If you are not doing any sport then come along and help tidy up school grounds",
      "org_id": 164125131157521,
      "org_name": "St Stithians Boys' College",
      "org_type": "S",
      "recurrence": "Weekly",
      "start_date": "2020-06-01",
      "end_date": "2021-12-31",
      "days_of_week": [
        "Monday",
        "Tuesday",
        "Wednesday",
        "Thursday",
        "Friday"
      ],
      "start_time": "14:00",
      "end_time": "15:00",
      "booking_closes": 100,
      "capacity": 60,
      "slots_booked": 0,
      "slots_available": 60,
      "street": "40 Peter Place",
      "suburb": "Lyme Park",
      "city": "Sandton",
      "province": "Gauteng",
      "email": "info@stithian.com",
      "telephone": "011 577 6000",
      "website": "https://www.stithian.com/",
      "gps_coords": "W299+47 Sandton",
      "images": [
        {
          "image_id": 164125131673650,
          "image_type": "thumbnail",
          "image_size": 60
        }
      ],
      "event_dates": [
        "2021-05-31",
        "2021-06-01",
        "2021-06-02",
        "2021-06-03",
        "2021-06-04",
        "2021-06-07",
        "2021-06-08",
        "2021-06-09",
        "2021-06-10",
        "2021-06-11",
        "2021-06-14",
        "2021-06-15",
        "2021-06-16",
        "2021-06-17",
        "2021-06-18",
        "2021-06-21",
        "2021-06-22",
        "2021-06-23",
        "2021-06-24",
        "2021-06-25",
        "2021-06-28"
      ]
    }
  ]
}
```


