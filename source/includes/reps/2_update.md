## Update Charity Rep Details
This endpoint can be used to update all details of a charity representative.

On successful completion rep details will be included in the JSON response.

```shell
http PUT example.com/api/reps/{id}
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/reps/2327833979673121796`

### Parameters

Parameter | Description
--------- | -----------
email | "charity2@mail.org"
first_name | "Harder"
last_name | "Worker"
mobile | "08512345657"
date_of_birth | "2011-02-03"
gender | "M"
id_type | "P"
id_number | "908075"
charity_id | 166133256908824

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": {
        "user_id": 166133281919052,
        "email": "charity2@mail.org",
        "first_name": "Harder",
        "last_name": "Worker",
        "mobile": "08512345657",
        "date_of_birth": "2011-02-03",
        "gender": "M",
        "id_type": "P",
        "id_number": "908075",
        "charity_id": 166133256908824
    }
}
```
