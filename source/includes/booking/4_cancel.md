## Cancel Event Booking
This endpoint allows an event booking to be cancelled.

I still need to send notifications to student and parent

```shell
http PUT example.com/api/bookings/{id}/cancel
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/bookings/164352822259788/cancel`

### Parameters

Parameter | Description
--------- | -----------
comments | Any comments that are associated with the cancellation

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
