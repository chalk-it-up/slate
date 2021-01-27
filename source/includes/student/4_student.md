## List Student Event Bookings
This endpoint can be used to list the events booked by a student.

```shell
http GET example.com/api/students/:id/events
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/students/2327833979673121796/events`

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": [
        {
            "booking_id": 120960836751396,
            "charity_id": 120960812077064,
            "charity_name": "Ark Animal Centre & Puppy Shelter",
            "event_id": 120960812535832,
            "event_name": "Animal Care",
            "start_time": "14:00",
            "end_time": "16:00",
            "status": "B",
            "comments": "Booking comments",
            "updated_by": 120960813019171,
            "updated_by_name": "Joe Soap",
            "updated_by_email": "child1@mail.org"
        }
    ]
}
```
