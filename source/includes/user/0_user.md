# User

## User Details
This endpoint returns useful information pertaining to the specified user.
 
```shell
http GET example.com/api/users/:id
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/users/:id`

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "data": {
        "id": 2129666729394050204,
        "email": "chalky@example.com",
        "first_name": "First",
        "last_name": "Account",
        "email_confirmed": false,
        "profile_complete": false,
        "time_created": "2010-06-09T18:17:36.641",
        "user_type": "P"
    }
}
```
