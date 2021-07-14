## Complete Event Booking
This endpoint allows an event booking to be completed.

This handler needs work on the validation:
- cannot complete until the event is over

I also still need to send notifications to student, parent and organisation

```shell
http PATCH example.com/api/bookings/164352822259788
```

```javascript
TODO
```

### HTTP Request

`PATCH example.com/api/bookings/{id}`

### Parameters

Parameter | Description
--------- | -----------
comments | Any comments that are associated with the booking (optional)
status | A value of 'Completed'

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": [
        {
          "booking_id": 180464041250906,
          "comments": "Booking comments",
          "status": "Cancelled",
          "updated_by": 180464014979155
        }
    ]
}
```
