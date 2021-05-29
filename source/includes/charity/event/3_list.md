## Get All Events for a Charity
This endpoint returns a list of events associated with a charity.
 
```shell
http GET example.com/api/events?org_id=96042186387470
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
        "event_id": 164128699691079,
        "name": "Test Event #2",
        "description": "Longer text about event",
        "org_id": 164128677638172,
        "org_name": "Ekklesia Park",
        "org_type": "C",
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
        "slots_booked": 0,
        "slots_available": 15,
        "street": "2 Park Ln",
        "suburb": "Blairgowrie,",
        "city": "Randburg",
        "province_id": 3,
        "province": "Gauteng",
        "email": "info@ekklesiapark.co.za",
        "telephone": "011 886 1430",
        "website": "https://ekklesiapark.co.za/",
        "registration_number": "",
        "gps_coords": "",
        "tags": [
          "Disability"
        ],
        "images": []
      }
    ]
}
```
