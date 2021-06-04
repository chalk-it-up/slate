## Get Charity Rep Details
This endpoint returns the details for a single charity representative.
 
```shell
http GET example.com/api/reps/{id}
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/reps/123456`

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": {
      "user_id": 166133281919052,
      "email": "charity2@mail.org",
      "user_type": "C",
      "first_name": "Harder",
      "last_name": "Worker",
      "mobile": "08512345657",
      "date_of_birth": "2011-02-03",
      "gender": "M",
      "id_type": "P",
      "id_number": "908075",
      "email_confirmed": false,
      "profile_complete": false,
      "time_created": "2021-06-04T06:58:23.481378Z",
      "enabled": true,
      "charity_id": 166133256908824,
      "charity_name": "Ark Animal Centre ? Puppy Shelter",
      "images": []
    }
}
```
