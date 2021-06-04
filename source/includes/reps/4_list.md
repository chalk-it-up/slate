## Get All Charity Reps for a Charity
This endpoint returns a list of all charities.

```shell
http GET example.com/api/charities/{id}/reps
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/charities/166133256908824/reps`

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": [
        {
            "user_id": 166133256925217,
            "email": "ark@chalkitupsa.co.za",
            "images": []
        },
        {
            "user_id": 166133281919052,
            "email": "charity2@mail.org",
            "first_name": "Harder",
            "last_name": "Worker",
            "images": []
        }
    ]
}```
