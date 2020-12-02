## Get Event Booking Details
This endpoint returns the details for a single charity event booking.
 
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
        "booking_id": 101174887903267,
        "charity_id": 101174865088526,
        "charity_name": "Ekklesia Park",
        "street": "2 Park Ln",
        "suburb": "Blairgowrie,",
        "city": "Randburg",
        "province_id": 3,
        "event_id": 101174887313442,
        "event_name": "Test Event",
        "start_time": "16:00",
        "end_time": "17:00",
        "user_id": 101174865891358,
        "first_name": "John",
        "last_name": "Doe",
        "email": "charity@mail.org",
        "user_type": "C",
        "status": "B",
        "comments": "Booking comments..",
        "updated_by": 101174865891358,
        "updated_by_name": "John Doe",
        "updated_by_email": "charity@mail.org"
    }
}
```
