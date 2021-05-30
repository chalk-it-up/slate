## Complete Event Booking
This endpoint allows an event booking to be completed.

This handler needs work on the validation:
- cannot complete until the event is over

I also still need to send notifications to student, parent and organisation

```shell
http PUT example.com/api/bookings/{id}/complete
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/bookings/164352822259788/complete`

### Parameters

Parameter | Description
--------- | -----------
comments | Any comments that are associated with the booking

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": [
        {
          "booking_id": 164352822259788
        }
    ]
}
```
