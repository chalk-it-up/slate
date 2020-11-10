## Register
This endpoint is used to register a new user on the system
 
```shell
http POST example.com/register email=joe@soap.com password=secret user_type=C
```

```javascript
TODO
```

### HTTP Request

`POST example.com/register`

### Parameters
The register handler works in two different modes depending on whether the user is a student or an adult.

### User Type
The possible values for `user_type` can be:

Type | Description
---- | -----------
A | Administrator
S | Student
C | Charity
P | Parent or Guardian
T | Teacher

**(Student)**
When a student registers an email is sent to the student's parent to complete the registration process.
  
Parameter | Description
--------- | -----------
first_name | The first name of student that is registering 
parent_email | The email address of the studen't parent 
user_type | The type of user registering (must be `S`)

> The above command returns JSON structured like this:

```json
{
  "success": true,
  "message": "An email has been sent to the parent email address provided" 
}
```

**(Adult)**
  
Parameter | Description
--------- | -----------
email | The email address of the new user 
password | The password to be used for the new user
user_type | The type of user registering (must be `C`, `P` or `T`)

> The above command returns JSON structured like this:

```json
{
  "success": true,
  "data": {
    "user_id": 2325393376858483571,
    "token": "eyJ0eXAi.....7sjnwj",
    "user_type": "P",
    "roles": [
        "volunteer-owner",
        "charity-view",
        "school-list",
        "everyone"
    ]
  }
}
```

> In the event of a problem, the following JSON would be returned

```json
{
    "success": false,
    "message": "Registration failed",
    "data": [
        {
            "field": "email",
            "message": "The email address is not a valid format"
        }
    ]
}
```
