## Get Teacher Details
This endpoint returns the details for a single teacher.
 
```shell
http GET example.com/api/teachers/:id
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/teachers/123456`

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": {
        "user_id": 119471404773410,
        "email": "teacher@school.org",
        "first_name": "Mrs",
        "last_name": "Teacher",
        "user_type": "S",
        "mobile": "",
        "date_of_birth": "1970-01-01",
        "gender": "F",
        "id_type": " ",
        "id_number": "",
        "email_confirmed": false,
        "profile_complete": false,
        "time_created": "2021-01-23T10:30:43.547063Z",
        "last_login_time": "2021-01-23T10:30:48.055674Z",
        "enabled": true,
        "school_id": 119471403855875,
        "school_name": "St Stithians Boys' College",
        "images": [
            {
                "image_id": 116008417529898,
                "image_type": "banner",
                "image_size": 60
            },
            {
                "image_id": 116008417570859,
                "image_type": "thumbnail",
                "image_size": 60
            }
        ]
    }
}
```

