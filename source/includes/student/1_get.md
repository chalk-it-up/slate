## Get Student Details
This endpoint returns the details for a single student.
 
```shell
http GET example.com/api/students/{id}
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/students/123456`

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": {
        "user_id": 116008415440937,
        "email": "child2@mail.org",
        "first_name": "Jane",
        "last_name": "Soap",
        "mobile": "0802223333",
        "date_of_birth": "2010-01-01",
        "gender": "F",
        "grade": "7",
        "id_type": "P",
        "id_number": "456789",
        "email_confirmed": false,
        "profile_complete": false,
        "time_created": "2021-01-13T15:39:47.25217",
        "last_login_time": null,
        "enabled": true,
        "parent_id": 116008380338202,
        "school_id": 207681581397679,
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

