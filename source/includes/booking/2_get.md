## Get Event Booking Details
This endpoint returns the details for an event booking.
 
```shell
http GET example.com/api/bookings/96042210856992
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/bookings/{id}`

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": {
        "booking_id": 164352822956110,
        "org_id": 164352800968728,
        "org_name": "Ark Animal Centre & Puppy Shelter",
        "street": "2 Park Ln",
        "suburb": "Blairgowrie,",
        "city": "Randburg",
        "province_id": 3,
        "event_id": 101174887313442,
        "name": "Test Event",
        "description": "Longer text about event",
        "start_time": "16:00",
        "end_time": "17:00",
        "user_id": 164352801927242,
        "first_name": "Joe",
        "last_name": "Soap",
        "email": "child1@mail.org",
        "user_type": "S",
        "event_date": "2021-05-30",
        "status": "Booked",
        "comments": "Booking comments..",
        "images": [],
        "updated_by": 101174865891358,
        "updated_by_name": "John Doe",
        "updated_by_email": "charity@mail.org"
    }
}
```
