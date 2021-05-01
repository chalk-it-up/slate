# Events

## Searching for Events
This endpoint is used to search for events across all charities and schools.

```shell
http GET example.com/api/events
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/events`

### Parameters

Parameter | Description
--------- | -----------
province_id | Filters events to a single province (should always be used)
tag | Only return events matching the given tag
day | Filter events to a specified day of the week (E.g. "fri")
month | Only return events available in a given month (Numeric values from 1 - 12)
year | Will default to current year if not specified (E.g. 2021)
date_from | Used to restrict events to a date range (E.g. "2021-12-01")
date_to | Used to restrict events to a date range (E.g. "2021-12-31")
offset | The starting record (for pagination)
limit | The number of records to return

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": [
      {
        "event_id": 154169665400879,
        "name": "School Cleanup",
        "description": "If you are not doing any sport then come along and help tidy up school grounds",
        "org_id": 154169664901135,
        "org_name": "St Stithians Boys' College",
        "org_type": "S",
        "recurrence": "Weekly",
        "start_date": "2020-06-01",
        "end_date": "2021-12-31",
        "days_of_week": [
          "mon",
          "tue",
          "wed",
          "thu",
          "fri"
        ],
        "start_time": "14:00",
        "end_time": "15:00",
        "capacity": 100,
        "street": "40 Peter Place",
        "suburb": "Lyme Park",
        "city": "Sandton",
        "email": "info@stithian.com",
        "telephone": "011 577 6000",
        "website": "https://www.stithian.com/",
        "gps_coords": "W299+47 Sandton",
        "images": [
          {
            "image_id": 154169665425456,
            "image_type": "thumbnail",
            "image_size": 60
          }
        ],
        "event_dates": [
          "2021-05-03",
          "2021-05-04",
          "2021-05-05",
          "2021-05-06",
          "2021-05-07",
          "2021-05-10",
          "2021-05-11",
          "2021-05-12",
        ]
      },
    ]
}
```


