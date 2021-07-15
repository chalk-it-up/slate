## Cancel Event Booking
This endpoint allows an event booking to be cancelled.

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
comments | Any comments that are associated with the cancellation (optional)
status | A value of 'Cancelled'

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": [
        {
          "booking_id": 164352822259788,
          "comments": "Booking comments Updated",
          "status": "Cancelled",
          "updated_by": 180464014979155
        }
    ]
}
```
