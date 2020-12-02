# Charity Event Bookings

## Book Event 
This endpoint can be used to book a charity event.


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
event_id | The id of the event to be booked
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
