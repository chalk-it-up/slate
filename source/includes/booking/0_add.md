# Event Bookings

## Book an Event 
This endpoint can be used to book an event.


```shell
http POST example.com/api/events/101172896002082/bookings
```

```javascript
TODO
```

### HTTP Request

`POST example.com/api/events/{id}/bookings`

### Parameters

Parameter | Description
--------- | -----------
event_date | The date of the event to be booked
user_id | The user id booking the event
comments | Any comments that are associated with the booking

> The above command returns JSON structured like below where id is the identity of the event added.

```json
{
    "success": true,
    "data": {
        "booking_id": 96042210856992
    }
}
```
