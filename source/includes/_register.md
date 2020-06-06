## Register
This endpoint is used to register a new user on the system
 
```shell
http POST <%= config[:endpoint] %>/register
```

```javascript
TODO
```

### HTTP Request

`POST <%= config[:endpoint] %>/register`

### Parameters

Parameter | Description
--------- | -----------
email | The email address of the new user 
password | The password to be used for the new user
first_name | The first name of the new user
last_name | The last name, or surname, of the new user
user_type | The type of user registering

### User Type
The possible values for `user_type` can be:

Type | Description
---- | -----------
A | Administrator
V | Volunteer
C | Charity
P | Parent or Guardian
S | School
 
> The above command returns JSON structured like this:

```json
{
    "data": {
        "first_name": "Joe",
        "last_name": "Soap",
        "roles": [
            "volunteer-owner",
            "charity-view",
            "school-list",
            "everyone"
        ],
        "token": "eyJ0eXAi.....7sjnwj",
        "user_id": 2325393376858483571,
        "user_type": "V"
    }
}
```
