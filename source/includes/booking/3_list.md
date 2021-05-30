## List Event Bookings
This endpoint list bookings for an event.
 
```shell
http GET example.com/api/events/101174887313442/bookings
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/events/{id}/bookings`

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": [
        {
            "booking_id": 101174887903267,
            "user_id": 101174865891358,
            "first_name": "John",
            "last_name": "Doe",
            "email": "charity@mail.org",
            "status": "Booked",
            "comments": "Booking comments"
        }
    ]
}
```
