## List Student Event Bookings
This endpoint can be used to list the events booked by a student.

```shell
http GET example.com/api/students/{id}/events
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
          "booking_id": 154159234887748,
          "org_id": 154159209902095,
          "org_name": "St Stithians Boys' College",
          "event_id": 154159210541103,
          "name": "School Cleanup",
          "description": "If you are not doing any sport then come along and help tidy up school grounds",
          "start_time": "14:00",
          "end_time": "15:00",
          "status": "B",
          "comments": "Booking comments",
          "images": [
            {
              "image_id": 154159210565680,
              "image_type": "thumbnail",
              "image_size": 60
            }
          ],
          "updated_by": 154159211016259,
          "updated_by_name": "Joe Soap",
          "updated_by_email": "child1@mail.org"
        }
    ]
}
```
