# Charity Reps

## Add Charity Rep
This endpoint can be used to add a new charity representative.

On successful completion rep details will be included in the JSON response.
 
```shell
http POST example.com/api/reps
```

```javascript
TODO
```

### HTTP Request

`POST example.com/api/reps`

### Parameters

Parameter | Description
--------- | -----------
email | "charity2@mail.org"
first_name | "Hard"
last_name | "Worker"
mobile | "0802223333"
date_of_birth | "2004-07-22"
gender | "M"
id_type | "P"
id_number | "456789"
charity_id | 166133256908824

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": {
      "email": "charity2@mail.org",
      "first_name": "Hard",
      "last_name": "Worker",
      "charity_id": 166133256908824,
      "user_id": 166133281919052
    }
}
```
