## Update Event Booking 
This endpoint can be used to move a booking to a new date or to update an event booking comments.


```shell
http PATCH example.com/api/bookings/101174887903267
```

```javascript
TODO
```

### HTTP Request

`PATCH example.com/api/bookings/{id}`

### Parameters
The following request parameters are optional.

Parameter | Description
--------- | -----------
event_date | The date of the event to be booked
comments | Any comments that are associated with the booking

> The above command returns JSON structured like below where id is the identity of the event added.

```json
{
  "success": true,
  "message": "Ok",
  "data": {
    "booking_id": 164352822956110,
    "comments": "Booking comments Updated",
    "event_date": "2021-06-28",
    "status": "Booked",
    "updated_by": 164352801927242
  }}
```
